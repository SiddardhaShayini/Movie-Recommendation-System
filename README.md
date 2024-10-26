# Movie Recommendation System
This project is a simple Movie Recommendation System that suggests movies based on similarity to a given movie, using the Nearest Neighbors algorithm.

## Overview
The system recommends movies based on features like genre and popularity. Built with Python and common data science libraries, it provides basic recommendations based on nearest neighbors.

## Dataset
The dataset includes 4,767 movie records with columns such as title, genre, popularity, and more. The data file is accessible at the following URL:
`Movies Recommendation.csv`

## Usage
### 1. Run the Notebook in Google Colab or locally:

    **Load the dataset**.
    **Preprocess the data**.
    **Use the recommendation function to input a movie title and get suggestions**.
### 2. Example:

```python
recommended_movies = recommend_movies('Inception', model, movies_df)
if not recommended_movies.empty:
    print(recommended_movies[['Movie_Title', 'Movie_Genre']])
else:
    print("No recommendations available. Please check the movie title.")
