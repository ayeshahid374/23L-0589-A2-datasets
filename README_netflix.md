# Netflix Titles - Cleaned Dataset

File: 23L_0589_A2_netflix_cleaned.csv

Version: v1.0

Date: 18 October 2026

Author: Ayesha Shahid

## Original source
Netflix Movies and TV Shows dataset on Kaggle (netflix_titles.csv):
https://www.kaggle.com/datasets/shivamb/netflix-shows
The original data belongs to its authors. Please check the licence on the Kaggle page.

## What I changed
- director, cast, country and rating: missing values filled with "Unknown".
- 3 movies had their length in the rating column. I moved it to duration and set rating to "Unknown".
- date_added: removed extra spaces and converted to datetime. 10 values are still missing.
- duration: split into movie_minutes and season_count.
- Outliers (old titles, very long or short movies, many seasons) were kept.
- No rows were removed (8,807 rows).

## New columns
year_added, month_added, years_to_add, movie_minutes, season_count, num_countries, num_genres, primary_country
