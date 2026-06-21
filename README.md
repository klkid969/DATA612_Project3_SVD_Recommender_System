# DATA 612 Project 3: Matrix Factorization with SVD

## Overview

This project demonstrates the use of Singular Value Decomposition (SVD) as a matrix factorization technique within a recommender system.

A synthetic movie-ratings dataset comprising 50 users and 20 real movie titles was created to simulate user preferences. Missing ratings were handled using movie-average imputation, and Truncated SVD was applied to identify latent factors representing hidden rating patterns.

The latent factors were then used to reconstruct the ratings matrix, generate predicted ratings, and produce movie recommendations. Model performance was evaluated using Mean Absolute Error (MAE).

## Methods

* Create ratings matrix
* Analyze missing values
* Impute missing ratings using movie averages
* Apply Truncated SVD
* Reconstruct ratings matrix
* Evaluate reconstruction accuracy using MAE
* Generate movie recommendations
* Visualize recommendation results

## Results

* Dataset Size: 50 Users × 20 Movies
* Missing Ratings: 15.3%
* Latent Factors: 5
* Mean Absolute Error (MAE): 0.7243

Top recommendations for User_1 included:

* Get Out
* The Social Network
* The Lion King
* Goodfellas
* Jurassic Park

## Conclusion

This project demonstrated how matrix factorization can reduce the dimensionality of a ratings matrix while preserving important rating patterns. The SVD model successfully reconstructed the ratings matrix and generated meaningful recommendations based on learned user preferences.
