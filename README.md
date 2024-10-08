# Unsupervised Learning Repository

## Overview
This repository contains implementations of various unsupervised machine learning algorithms, with a focus on clustering and dimensionality reduction techniques. Unsupervised learning involves discovering hidden patterns or intrinsic structures in data without labeled responses. This is useful for tasks such as data exploration, anomaly detection, and feature extraction.

The repository is organized into different subfolders, each dedicated to a specific algorithm or technique.

- [**`dimensionality-reduction/`**](https://github.com/jessherna/unsupervised-learning/tree/master/dimensionality-reduction/pca): Contains projects related to reducing the dimensionality of data, such as PCA.

## Projects

### 1. Dimensionality Reduction
This section includes projects that focus on reducing the dimensionality of datasets while retaining as much important information as possible. 
- **PCA (Principal Component Analysis)**: 
    - [`PCA_MNIST.ipynb`](https://github.com/jessherna/unsupervised-learning/blob/master/dimensionality-reduction/pca/PCA_MNIST.ipynb): Applies PCA to the MNIST dataset to reduce its dimensions and visualize the most significant components.
    - [`PCA_SwissRoll.ipynb`](https://github.com/jessherna/unsupervised-learning/blob/master/dimensionality-reduction/pca/PCA_SwissRoll.ipynb): Applies kernel trick to PCA using the Swiss Roll dataset to perform complex nonlinear projections.

### 2. Clustering
This section includes projects that focus on techniques on clustering.
    - [`KMeans_DBSCAN.ipynb`](https://github.com/jessherna/unsupervised-learning/blob/master/clustering/KMeans_DBSCAN.ipynb): Applies Kmeans and DBSCAN to the Olivetti Faces dataset to determine the clusters.
    - [`Hierarchical_Clustering.ipynb`](https://github.com/jessherna/unsupervised-learning/blob/master/clustering/Hierarchical_Clustering.ipynb): Applies Hierarchical Clustering to the Olivetti Faces dataset to determine the clusters.


## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
