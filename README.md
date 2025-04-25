# collaborative-filtering-recommender
 Movie Recommendation System using Item-based Collaborative Filtering

This project implements an *Item-based Collaborative Filtering* recommender system using the [MovieLens 100K dataset](https://grouplens.org/datasets/movielens/100k/). The goal is to recommend movies to users based on their previous ratings and the similarity between items.

## Files Included

- 03_item_based_cf.ipynb:  
  Contains the implementation of the Item-based Collaborative Filtering model using the Surprise library.

- 04_evaluation_and_visualization.ipynb:  
  Evaluates the model using metrics like RMSE, Precision@K, Recall@K, and provides visualizations such as prediction error distribution and a confusion-matrix-like heatmap.

## Dataset

This project uses the following files from the MovieLens 100K dataset:
- u.data: User ratings (user_id, item_id, rating, timestamp)
- u.item: Movie metadata (item_id, movie_title, etc.)
