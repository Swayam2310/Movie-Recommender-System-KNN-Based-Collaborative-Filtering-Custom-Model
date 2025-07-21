# Movie-Recommender-System-KNN-Based-Collaborative-Filtering-Custom-Model

This project focuses on building and evaluating a movie recommendation system using collaborative filtering techniques on the MovieLens 1M dataset. The system implements both user-based and item-based KNN approaches, and also explores a custom model to enhance recommendation accuracy and relevance.

## Project Overview

The goal is to predict user preferences for movies based on past user ratings and item similarities. The project consists of three main approaches:

- **User-Based Collaborative Filtering:** Predicts a target user's movie ratings using the preferences of similar users.
- **Item-Based Collaborative Filtering:** Recommends movies by identifying items similar to those the user has previously rated.
- **Custom Recommender System:** Implements a more advanced algorithm to improve precision and ranking performance over traditional methods.

## Dataset

The project uses the [MovieLens 1M Dataset](https://grouplens.org/datasets/movielens/1m/) containing 1 million ratings from 6,000 users on 4,000 movies. The dataset includes:
- User demographic data
- Movie metadata
- Timestamped ratings

## Techniques Used

- **KNN (K-Nearest Neighbours):** for both user-user and item-item similarity
- **Similarity Metrics:** Cosine similarity and Pearson correlation
- **Evaluation Metrics:**
  - RMSE (Root Mean Square Error)
  - Average Precision (AP)
  - Normalized Discounted Cumulative Gain (NDCG)
- **Custom Model Implementation:** Incorporates literature-based or novel methodology to improve top-N recommendations
