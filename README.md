# Movie-Recommendation
This repository contains a simple content-based movie recommendation system built using Python. The system analyzes the similarity between movies based on their genres and titles, providing personalized movie recommendations.

Features

    Dataset: Utilizes the Movie Recommendation Dataset, which contains information about movies, including their titles and genres.
    Preprocessing: Combines movie genres and titles into a single feature to create a meaningful text representation for each movie.
    TF-IDF Vectorization: Converts the combined text features into numerical vectors using TfidfVectorizer.
    Cosine Similarity: Calculates the similarity scores between movies based on their TF-IDF representations.
    Recommendation Function: Returns the top 10 movies most similar to a given movie title.

How It Works

    Data Extraction: The dataset is extracted from a ZIP file.
    Data Preprocessing: Missing values are checked, and combined features are created by concatenating genres and titles.
    Feature Engineering: Text data is vectorized using TF-IDF to create a similarity matrix.
    Recommendation: A function get_movie_recommendations() identifies and ranks the most similar movies for a given input.

Example Usage

For the input movie "Hitman (2007)", the system recommends 10 similar movies based on genres and title similarity.
