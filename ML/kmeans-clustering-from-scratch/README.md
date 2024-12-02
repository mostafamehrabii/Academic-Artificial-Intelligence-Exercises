
### GitHub Description:

This Jupyter Notebook implements the K-Means clustering algorithm from scratch using the "Wholesale customers data" dataset. The notebook walks through the following steps:

1. **Data Preparation**: 
   - Loads the dataset.
   - Normalizes the features.
   - Prepares data for clustering by removing unnecessary columns (`Channel` and `Region`).

2. **Centroid Initialization**: 
   - Custom implementation for initializing centroids using a probabilistic approach.

3. **Cluster Assignment**: 
   - Assigns data points to the nearest centroid.

4. **Centroid Update**: 
   - Recomputes centroids based on the mean of points in each cluster.

5. **Convergence**: 
   - Iterates the assignment and update steps until centroids stabilize.

6. **Performance Evaluation**: 
   - Calculates Sum of Squared Errors (SSE).
   - Computes Silhouette Score for the clustering results.

7. **Visualization**: 
   - Plots the Elbow Method (SSE vs. number of clusters).
   - Displays Silhouette Scores for different cluster numbers.

---

### Features:
- **Custom K-Means Implementation**: No external clustering libraries are used.
- **Performance Metrics**: SSE and Silhouette Score are calculated to assess clustering quality.
- **Optimal Cluster Identification**: Elbow Method and Silhouette Score plots help determine the best value for `k`.

---

### Instructions:
1. Place the dataset file (`Wholesale customers data.csv`) in the same directory as this notebook.
2. Open the notebook in Jupyter or any compatible environment.
3. Execute the cells sequentially to perform K-Means clustering and visualize the results.

---

### Outputs:
- **Metrics**: SSE and Silhouette Score for the final clusters.
- **Plots**:
  - Elbow Method plot for determining optimal `k`.
  - Silhouette Score plot for assessing cluster quality. 

---

This notebook is ideal for learning and experimenting with the K-Means clustering algorithm through a hands-on approach.
