# MovieLens Recommender System
This repository contains a comprehensive movie recommender system built in Python. 
The system utilizes multiple machine learning techniques to provide personalized movie recommendations. 
The primary techniques include K-Nearest Neighbors (KNN), cosine similarity, and matrix factorization. 
### K-Nearest Neighbors (KNN)
The KNN algorithm recommends movies based on the proximity of user preferences. 
It works by finding the 'k' nearest users (or items) to a given user (or item) based on their ratings.
The preferences of these neighbors are then used to generate recommendations.
### Cosine Similarity
Cosine similarity measures the cosine of the angle between two non-zero vectors in an inner product space. 
In the context of movie recommendations, it is used to determine the similarity between users or items based on their ratings.
### Matrix Factorization
Matrix factorization techniques, such as Singular Value Decomposition (SVD), decompose the user-item interaction matrix into lower-dimensional representations. 
This method is widely used in collaborative filtering to capture latent factors influencing user preferences.

## Libraries used
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn
 - Scikit-learn
 - FuzzyWuzzy
