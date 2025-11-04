# Netflix_Recommendation

## Netflix Recommendation System

This project is a mix of data exploration, visualization, and machine learning. I’ve built a content-based recommendation system using the Netflix titles dataset, which suggests similar movies or TV shows based on their content features like genre, director, cast, and description.

## Project Summary

The goal was to understand the type of content available on Netflix and then build a recommendation model that can suggest titles similar to a given movie or show.

Here’s what I did step by step:

## Data Exploration & Cleaning

Loaded the dataset and checked missing values.

Cleaned and formatted columns like director, cast, country, and date_added.

Converted text data into a structured format for modeling.

## Data Visualization

Created a word cloud to highlight the most common words in titles.

Analyzed the distribution of content type (Movies vs. TV Shows).

Explored top genres, countries, ratings, and most active directors/actors using interactive Plotly charts.

Looked at how Netflix content evolved over the years.

## Recommendation Model


Preprocessed text data using lemmatization and stopword removal.

Combined key metadata into one column.

Used TF-IDF Vectorization to represent the text numerically.

Calculated cosine similarity to find the most similar titles.
