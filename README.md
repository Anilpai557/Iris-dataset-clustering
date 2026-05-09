# Iris Dataset Clustering using Machine Learning

## Project Overview
This project demonstrates the application of two clustering algorithms on the Iris dataset:

- KMeans Clustering
- Hierarchical Clustering

The Iris dataset is loaded from the sklearn library and preprocessed by removing the species column since clustering is an unsupervised learning task.

---

# Dataset
The dataset used is the famous Iris flower dataset available in sklearn.datasets.

Features used:
- sepal length
- sepal width
- petal length
- petal width

Target/species column is removed before clustering.

---

# Algorithms Used

## 1. KMeans Clustering
KMeans clustering groups data points into K clusters based on distance from cluster centroids.

### Steps:
1. Select number of clusters
2. Initialize centroids
3. Assign points to nearest centroid
4. Update centroids
5. Repeat until convergence

---

## 2. Hierarchical Clustering
Hierarchical clustering builds clusters step-by-step using a tree-like structure called a dendrogram.

### Approach Used:
- Agglomerative Hierarchical Clustering (Bottom-Up)

---

# Output

The notebook includes:
- Data preprocessing
- KMeans clustering visualization
- Hierarchical clustering visualization
- Dendrogram visualization

---

# Sample Visualizations

- Scatter plots of clusters
- Cluster centroids
- Dendrogram for hierarchical clustering

---

# Conclusion

Both KMeans and Hierarchical clustering algorithms successfully identified natural groupings in the Iris dataset.

- KMeans efficiently separated the dataset into clusters.
- Hierarchical clustering provided additional insights using dendrograms.
