### README: SVM Classifier with Visualization

This project demonstrates the implementation of a Support Vector Machine (SVM) classifier from scratch in Python. It includes functionality for classifying data, handling imbalanced datasets through class weighting, and visualizing the decision boundary.

---

### Features

1. **Custom SVM Implementation**:
   - Implements SVM with hinge loss and L2 regularization.
   - Supports binary classification with adjustable learning rate, regularization parameter, and number of iterations.

2. **Handling Imbalanced Data**:
   - Dynamically adjusts class weights based on class distribution to improve performance on imbalanced datasets.

3. **Visualization**:
   - Visualizes the SVM decision boundary, support vectors, and margins.

4. **Synthetic Data Generation**:
   - Generates synthetic datasets with two clusters for testing using the `make_blobs` function.

5. **Metrics**:
   - Calculates and displays classification accuracy on the test dataset.

---

### Requirements

The script requires the following Python libraries:
- `numpy`
- `matplotlib`
- `pandas`

Install them using:
```bash
pip install numpy matplotlib pandas
```

---

### How to Run

1. Clone the repository or download the file `svm_classifier_with_visualization.py`.
2. Open the script and run it in any Python environment (e.g., Jupyter Notebook, VS Code, or command line).
3. The script will:
   - Generate synthetic data.
   - Train the SVM classifier on the training set.
   - Evaluate it on the test set.
   - Visualize the decision boundary.

---

### Code Configuration

1. **Data Settings**:
   - The `make_blobs` function generates data with configurable sample sizes, features, clusters, and randomness.
   - Example: `make_blobs(n_samples_per_class=[200, 500], n_features=2, centers=2, random_state=40)`

2. **Model Parameters**:
   - `learning_rate`: Step size for gradient descent (default: `0.001`).
   - `lambda_param`: Regularization strength (default: `0.01`).
   - `n_iters`: Number of iterations for training (default: `1000`).

3. **Train-Test Split**:
   - The `train_test_split` function splits the data into training and test sets. Default test size is `20%`.

---

### Output


1. **Decision Boundary Plot**:
   Displays a plot showing:
   - Decision boundary (dashed line).
   - Positive and negative margins.
   - Data points colored by their class.

---

### Example Usage

1. **Synthetic Data Generation**:
   - Generate imbalanced data with `200` samples in one class and `500` in another.

2. **Visualization**:
   - The decision boundary is plotted, showing how the SVM separates the two classes.

---

### Notes

- The implementation uses gradient descent for optimization.
- The code demonstrates handling imbalanced classes by assigning higher weights to smaller classes.
- This implementation is educational and may not be as efficient as libraries like `scikit-learn`.

---

### Future Improvements

- Add multi-class classification support.
- Implement kernel functions for non-linear separable data.
- Optimize the code for larger datasets.

---

This project serves as an introduction to SVMs and provides a foundation for further exploration and optimization in machine learning.
