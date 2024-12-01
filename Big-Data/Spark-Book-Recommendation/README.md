```markdown
# Recommender System Using PySpark

This project demonstrates how to build a book recommendation system using PySpark. The dataset consists of user ratings for books, and the Alternating Least Squares (ALS) algorithm is utilized for generating personalized book recommendations.

## Prerequisites

Ensure the following Python packages are installed:
- `pyspark`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

You can install PySpark using:
```bash
pip install pyspark
```

## Steps

1. **Initialize Spark Session**  
   A Spark session is created to process the data and build the recommendation system.

2. **Data Loading**  
   Load the dataset (`Ratings.csv`) containing user ratings for books.

3. **Data Preprocessing**  
   Use `StringIndexer` to convert book identifiers (`ISBN`) into numeric indices required for ALS.

4. **Model Training**  
   - Split the data into training and testing sets.
   - Train an ALS model using the training set.
   - Evaluate the model using RMSE on the testing set.

5. **Book Recommendation**  
   A function `top_books` is implemented to recommend top `n` books for a given user. It filters out books already rated by the user and ranks unrated books based on predicted ratings.

6. **Output**  
   Display recommended books for the user with their predicted ratings.

## How to Run

1. Upload the dataset (`Ratings.csv`) to the environment.
2. Run the Python script sequentially.
3. Call the `top_books(user_id, n)` function to get book recommendations for a specific user.

## Example

To get 5 book recommendations for a user with ID `75149`:
```python
top_books(75149, 5)
```

## Results

The output includes:
- Books already read by the user.
- Books yet to be rated by the user.
- Top recommendations based on predicted ratings.

## Dataset

The dataset can be downloaded from [this link](https://s32.picofile.com/d/8479862176/4d184cfb-b74d-49ed-969c-ccdf60ddece3/Ratings-csv).
