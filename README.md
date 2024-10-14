# iris-pca-dbscan
1) Description:
    This project implements a DBSCAN clustering algorithm on the Iris dataset, enhanced by dimensionality reduction through Principal Component Analysis (PCA), showing the effectiveness of clustering techniques on standardized data.

2) Key Features:
  Dataset Utilization: Loads the Iris dataset with 150 samples and 4 features, standardizing the features for improved performance.
  PCA Implementation: Reduces dimensionality by projecting the data onto the top 2 principal components (Q=2) for easier visualization and clustering.
  DBSCAN Algorithm: Implements DBSCAN from scratch, classifying data points into clusters based on density, with parameters epsilon (eps) set to 0.5 and minimum points (MinPoints) set to 5.
  Visualization: Displays the original dataset and PCA-transformed dataset, highlighting clusters identified by DBSCAN, along with a comparison of clustered vs. non-clustered PCA data.

3) Programming Tools:
4)  Python, NumPy, Matplotlib, Scikit-learn.
