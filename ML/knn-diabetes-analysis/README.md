### README: KNN Diabetes Analysis

This project uses the K-Nearest Neighbors (KNN) algorithm to classify diabetes cases based on the given dataset. It includes model evaluation with and without data scaling and visualization of performance metrics.

---

#### Features:
1. **Dataset**: Utilizes the `diabetes.csv` file for training and testing.
2. **Data Splitting**: Divides the dataset into training and testing sets (80/20 split).
3. **KNN Implementation**: 
   - Evaluates the model for different values of K.
   - Compares results with and without scaling.
4. **Performance Metrics**:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
5. **Visualization**: 
   - Plots metric trends for various K values with and without scaling.
   - Compares results side by side.

---

#### Requirements:
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

Install the required libraries using:
```bash
pip install numpy pandas matplotlib scikit-learn
```

---

#### How to Run:
1. Ensure the dataset `diabetes.csv` is in the same directory as the script.
2. Run the script or notebook:
   ```bash
   python knn_diabetes_analysis.py
   ```
   Or in Jupyter Notebook:
   ```bash
   jupyter notebook knn_diabetes_analysis.ipynb
   ```

---

#### Output:
- Best K values for each metric (accuracy, precision, recall, F1-score) with and without scaling.
- Plots comparing metric performance for scaled and non-scaled data.
