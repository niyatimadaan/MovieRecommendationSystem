# Movie Recommendation System

This project is a movie recommendation system built using Python and several libraries such as pandas, sklearn, pickle, and Streamlit. It uses a dataset of movies to generate recommendations based on similarity scores between movies. Additionally, it uses the TMDB API to fetch movie posters.

# Features
Loads a CSV dataset of movies
Fetches movie posters from TMDB API
Performs exploratory data analysis
Extracts features from the dataset
Generates movie recommendations based on similarity scores
Saves the processed data and similarity matrix for future use
Provides a user interface using Streamlit

# Installation
To use this project, you need to have Python installed on your machine. You also need to install the following Python libraries:

pandas
sklearn
pickle
streamlit
requests

# Usage
To use the movie recommendation system, follow these steps:

Run the Streamlit app:
streamlit run app.py
In the Streamlit app, select a movie from the dropdown menu.
Click the "Show Recommendations" button to get movie recommendations based on the selected movie.