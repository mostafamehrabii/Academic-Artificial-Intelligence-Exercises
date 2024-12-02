Linear Regression for Admission Prediction

This project implements a linear regression model using gradient descent to predict admission chances based on given features. It includes the following functionalities:

1. **Data Preprocessing**:
   - Removal of unnecessary columns.
   - Normalization of feature values using mean and standard deviation.

2. **Splitting the Dataset**:
   - The dataset is divided into training and testing sets, typically using an 80/20 split.

3. **Model Training**:
   - The linear regression model is trained using gradient descent, optimizing the cost function.
   - Cost values are calculated and plotted across iterations to visualize convergence.

4. **Model Evaluation**:
   - Metrics such as Mean Squared Error (MSE) and R-squared (R²) are used to assess the model's performance on test data.

5. **Visualization**:
   - A cost vs. iterations plot is generated to show the progress of training.

### Requirements

The script requires the following Python libraries:
- numpy
- pandas
- matplotlib

You can install them using pip:
```bash
pip install numpy pandas matplotlib
```

### Results

1. **Cost over iterations**:
   At key points during training, the cost function values are as follows:
   - Iteration 0: Cost = 0.2759
   - Iteration 100: Cost = 0.0369
   - Iteration 200: Cost = 0.0069
   - Iteration 300: Cost = 0.0028
   - Iteration 400: Cost = 0.0022
   - Iteration 500: Cost = 0.0021

2. **Evaluation Metrics**:
   - Mean Squared Error (MSE) on evaluation data: 0.0042

### How to Run

اگر فایل شما به صورت **Jupyter Notebook** (`.ipynb`) است، توضیحات در فایل `README.md` باید به این شکل تغییر داده شود:

---

1. Place the dataset (`Admission_Predict.csv`) in the same directory as the Jupyter Notebook file (`linear_regression_admission_predict.ipynb`).
2. Update the `file_path` variable in the notebook to point to your dataset location.
3. Open the notebook in Jupyter Notebook or JupyterLab and run all the cells sequentially.


### Dataset

The dataset contains information such as test scores, GPA, and other features related to admission prediction. Ensure that the dataset is in CSV format and properly structured.

### Additional Notes

This project serves as a foundational implementation of linear regression using gradient descent. It can be further extended to include more advanced features or methods, such as regularization, polynomial regression, or automated hyperparameter tuning.
