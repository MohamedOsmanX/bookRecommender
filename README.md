
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

The dataset that has been used is the [Book Recommendation Dataset]([https://www.kaggle.com/datasets/ruchi798/bookcrossing-dataset/data](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset/data)) dataset.

### The Book-Crossing dataset comprises 3 files.

#### Users:
Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL-values.
#### Books:
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavours (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon web site.
#### Ratings:
Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

