# Book Recommendation System Using Spark

This project implements a book recommendation system using PySpark's `ALS` (Alternating Least Squares) algorithm. The goal is to recommend books to users based on their previous ratings, leveraging collaborative filtering techniques.

## Features
- **Dataset Handling**: Processes a user-book rating dataset (`Ratings.csv`) to prepare it for recommendation.
- **Data Transformation**: Converts categorical data using `StringIndexer` for machine learning compatibility.
- **Recommendation System**: Uses the `ALS` algorithm to recommend books that a user has not rated yet.
- **Model Evaluation**: Calculates the Root Mean Square Error (RMSE) to measure the accuracy of predictions.
- **Top-N Recommendations**: Provides a function to recommend the top `n` books for a given user.

## Prerequisites
- Python
- PySpark
- Required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`

## Usage
1. **Install Dependencies**: Ensure you have PySpark installed (`pip install pyspark`).
2. **Load Dataset**: Upload the `Ratings.csv` file when prompted.
3. **Run the Code**: The script processes the dataset, trains the model, and evaluates its performance.
4. **Get Recommendations**: Use the `top_books(user_id, n)` function to recommend books for a specific user.

## Objective
The primary objective is to predict user preferences and recommend books based on collaborative filtering techniques, improving user experience in book discovery.
