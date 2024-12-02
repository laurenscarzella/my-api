# Overview:
This repository contains information on collecting, cleaning, and analyzing movie data. This project gathers data using the [TMBD API](https://developer.themoviedb.org/reference/intro/getting-started), preparing the data for analysis, and exploring valuable insights through summary statistics and data visualizations.

# Repository Contents:
1. .gitignore
- This file contains any information that I do not want to share publicly. For example, I stored my API key in this file to keep it private.

2. EDA.ipynb
- This file includes code for exploring the cleaned dataset.
- Produces summary statistics and bar charts for variables of interest.

3. cleaned_movies.csv
- Contains the cleaned and processed version of the movie dataset for analysis.

4. gather_data.ipynb
- This file contains code to interact with the TMBD API and gather movie data.
- It also goes over how to clean the data in preparation for the analysis.

5. movie_data.csv
- Contains the messy, unprocessed movie data fetched from the TMDB API

# Getting Started:
Clone this repository and install the required libraries.

# Usage:
1. Gathering and Cleaning Data: Run the gather_data.ipynb to fetch data from the TMDB API, process it, and save it as a .csv.

2. Data Exploration: Explore the cleaned dataset with the EDA.ipynb. Change this code or add to it to explore the data yourself.

# Results:
- Summary Statistics: This gives us basic information about the dataset.
- Visualizations: Bar charts reveal the most popular movie genres and the most popular movies by genre.