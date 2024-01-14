# Book Recommendation System

## Overview

This repository contains code and resources for building a book recommendation system based on the Book Recommendation Dataset available on Kaggle. The dataset provides information about user ratings and book details, making it suitable for developing collaborative filtering-based recommendation systems.

## Dataset

The dataset can be found on Kaggle: [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

## Dataset Structure

- **books.csv:** Contains information about books, including book ID, title, author, and publication year.
- **users.csv:** Provides user details, including user ID and location.
- **ratings.csv:** Contains user ratings for books, linking user ID, book ID, and the corresponding rating.

# Recommendation System Approach

The recommendation system implemented in `recommendation_system.py` is based on collaborative filtering. It analyzes user ratings to identify patterns and similarities between users. Two main types of collaborative filtering are implemented:

1. **User-Based Collaborative Filtering:** Recommends books based on the preferences of users with similar tastes.

2. **Item-Based Collaborative Filtering:** Recommends books based on the similarity between items (books) and the user's previous preferences.

## Acknowledgments
- The dataset used in this project is provided by Arashnic on Kaggle.
- This work is inspired by the field of collaborative filtering and recommendation systems.

## License
This project is licensed under the MIT License.
