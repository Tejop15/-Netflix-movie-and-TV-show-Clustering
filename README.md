# Project Name
Netflix movie and TV show Clustering

## Table of Contents
-Understanding the dataset and problem statement.
-Efficient EDA
-Dealing with missing values and outliers
-Cleaning the document
-Exploring exceptional cases
-Pre processing- TFIDF/ bag of words
-Selecting the approach and algorithm to be used.
-Modeling- use at least 2 algorithms.
-Brief strategy for clusters formed.
-Conclusion.
-How is your project useful to stakeholders?

## Introduction
The goal of this project is to study the Netflix Dataset of movies and TV series from the third-party search engine Flixable till 2019. The objective is to employ NLP approaches to categorize material into relevant clusters in order to improve the user experience via a recommendation system. This will assist Netflix, which presently has over 220 million customers, avoid subscriber attrition. The dataset will also be studied in order to find insights and trends in the streaming entertainment sector.

The project was completed in the following steps:

1. Dealing with null values in the dataset.
2. Managing nested columns for better presentation (director, cast, listed_in, country).
3. Sorting the rating attribute into categories (adult, children's, family-friendly, and unrated).
4. Conducting Exploratory Data Analysis (EDA) to get insights on subscriber churn prevention.
5. Creating clusters with features such as director, cast, nation, genre, rating, and description, which were tokenized, preprocessed, and vectorized using the TF-IDF vectorizer.
6. Using PCA to reduce the dimensionality of the dataset in order to increase performance.
7. Using the K-Means Clustering and Agglomerative Hierarchical Clustering algorithms, determine appropriate cluster numbers (4 for K-Means, 2 for hierarchical clustering) using a variety of assessment techniques.
8. Creating a content-based recommender system for Netflix that uses a cosine similarity matrix to deliver individualized recommendations to users and decrease subscription churn.

This thorough analysis and suggestion system are projected to boost customer happiness, resulting in higher Netflix retention rates.

## Conclusions drawn from ML Model

Implemented K-Means Clustering and Agglomerative Hierarchical Clustering, to cluster the Netflix Movies TV show dataset.
The optimal number of clusters we are getting from K-means is 4, whereas for Agglomerative Hierarchical Clustering the optimal number of clusters are found out to be 2.
We chose Silhouette Score as the evaluation metric over distortion score because it provides a more intuitive and interpretable result. Also Silhouette score is less sensitive to the shape of the clusters.
Built a Recommendation system that can help Netflix improve user experience and reduce subscriber churn by providing personalized recommendations to users based on their similarity scores.
