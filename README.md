
 # Book Recommendation System
## Overview

This project implements a book recommendation system using the k-Nearest Neighbors (k-NN) algorithm. It processes user ratings and book data to recommend similar books based on a given title.

The recommendation system is built using Python and leverages libraries like pandas, scikit-learn for data processing, machine learning.

## Features

Filters infrequent users (less than 200 ratings) and books (less than 100 ratings).

Builds a user-item matrix for collaborative filtering.

Recommends books similar to a given title based on cosine similarity.

Includes visualizations to understand the dataset:

        Top-rated books
        Distribution of user ratings
        Distribution of book ratings

## Dataset

The dataset that has been used is the [Book-Crossing: User review ratings](https://www.kaggle.com/datasets/ruchi798/bookcrossing-dataset/data) dataset.
It contains 278,858 users (anonymized but with demographic information) providing 1,149,780 ratings (explicit / implicit) about 271,379 books.

