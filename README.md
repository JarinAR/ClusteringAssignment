# Clustering Algorithms Assignment

## Overview

This assignment demonstrates the implementation and application of various clustering algorithms on synthetic and real-world datasets. The focus is on clustering techniques such as K-Means, DBSCAN, Agglomerative Clustering, and hierarchical clustering, with visualization and evaluation techniques to analyze the clustering results. 

## Tasks

### 1. **Synthetic Data Generation and Clustering**

- **Task**: Generate synthetic datasets using the `make_blobs`, `make_moons`, and `make_circles` functions, and apply different clustering algorithms such as K-Means, DBSCAN, and Agglomerative Clustering.
- **Objective**: Understand the behavior of clustering algorithms on different types of data, including linearly separable and non-linearly separable data.

### 2. **K-Means Clustering with Cluster Centers**

- **Task**: Apply K-Means clustering to synthetic data and visualize the clustering result, including the cluster centers.
- **Objective**: Demonstrate how K-Means identifies cluster centers and visualize them on a scatter plot.

### 3. **Hierarchical Clustering and Dendrogram**

- **Task**: Apply Agglomerative Clustering with various linkage criteria (e.g., complete linkage) to real datasets such as Iris or synthetic data.
- **Objective**: Visualize the clustering process using a dendrogram, which provides a hierarchical view of clustering.

### 4. **DBSCAN Clustering**

- **Task**: Apply DBSCAN clustering to datasets such as Iris or synthetic data and visualize the results.
- **Objective**: Highlight how DBSCAN identifies clusters and noise points, and how the density-based approach handles varying cluster shapes.

### 5. **Dimensionality Reduction and Clustering**

- **Task**: Apply PCA (Principal Component Analysis) to reduce high-dimensional data (e.g., Digits dataset) to 2D or 3D, then perform clustering (e.g., K-Means) and visualize the results.
- **Objective**: Learn how dimensionality reduction techniques like PCA can improve visualization and interpretability of clustering results.

### 6. **Evaluation and Metrics**

- **Task**: Evaluate clustering results using metrics such as silhouette score, inertia, and cluster counts.
- **Objective**: Assess the quality of clustering and determine the optimal number of clusters for various algorithms.

## Dataset Details

### 1. **Iris Dataset**
- **Description**: The Iris dataset contains measurements of 150 iris flowers from three different species. It has 4 features: sepal length, sepal width, petal length, and petal width.
- **Use**: Clustering, classification, and visualization.

### 2. **Digits Dataset**
- **Description**: The Digits dataset consists of 8x8 pixel images of handwritten digits. There are 1797 8x8 images representing digits from 0 to 9.
- **Use**: Clustering, classification, and dimensionality reduction.

### 3. **Synthetic Data (make_blobs, make_moons, make_circles)**
- **Description**: Synthetic datasets generated using `make_blobs`, `make_moons`, and `make_circles`. These datasets are useful for testing clustering algorithms on controlled data with different shapes and distributions.
- **Use**: Evaluating clustering algorithms on non-linearly separable data.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/clustering-assignment.git
