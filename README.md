# Content-Based Music Recommender System

This repository contains the implementation of a content-based music recommendation system using a dataset of Spotify sourced from kaggle. The system recommends songs based on the similarity of their lyrical content and attributes.

## Overview

The content-based approach recommends songs by analyzing features such as song names, artists, and lyrics. It calculates similarity measures between songs using natural language processing techniques applied to the song lyrics.

## Datasets

The following datasets from Kaggle and a Spotify playlist were used in this project:

- **data.csv**
- **data_by_artist.csv**
- **data_by_genres.csv**
- **data_by_year.csv**
- **data_w_genres.csv**
- **spotify_dataset.csv**

## Files

- **content_based_music_recommender.ipynb**: Jupyter notebook containing the code and analysis for the content-based music recommendation system.
- **data**: Folder contains the CSV files containing the dataset used, including song names, artists, genres, etc... 

## Methodology

Collaborative Filtering Song Recommendation
The collaborative filtering approach recommends songs by comparing the similarity of users based on their ratings using the Pearson Correlation Coefficient. This coefficient measures the strength of a linear association between user preferences, invariant to scaling. A coefficient of 1 indicates similar user tastes, while -1 indicates opposite tastes.

Content-Based Filtering Song Recommendation
The content-based filtering approach recommends songs based on different distance calculation methods applied to normalized song data (df_normalized). Distance methods such as cosine similarity, Euclidean distance, or Hamming distance are used to measure similarity between songs. This approach focuses on recommending songs that are similar in terms of their attributes, such as song features, lyrics, and artist.
