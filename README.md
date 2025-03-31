# ML-Assignment
# Hierarchical Clustering for Wine Dataset

This project implements **Agglomerative Hierarchical Clustering** to group the **Wine dataset** into distinct clusters based on various wine attributes. The goal is to explore the clustering process, visualize the dendrogram, and evaluate the model’s performance using the **Adjusted Rand Index (ARI)**.

## Project Overview

The project utilizes **Agglomerative Clustering** to segment the wine data into 3 clusters representing different wine classes. A hierarchical tree (dendrogram) is plotted to visualize the clustering process. The model's performance is evaluated using the Adjusted Rand Index, which measures the similarity between the predicted clusters and the true labels.

### Key Steps:
1. **Data Loading**: Load the Wine dataset using the `load_wine()` method from `sklearn`.
2. **Data Preprocessing**: Standardize the features using `StandardScaler` to scale the data.
3. **Hierarchical Clustering**: Perform Agglomerative Hierarchical Clustering with Ward’s linkage method.
4. **Dendrogram Visualization**: Plot the dendrogram with color-coded labels to visualize the clustering process.
5. **Clustering Evaluation**: Evaluate the clustering performance using the Adjusted Rand Index (ARI) to measure how well the clusters align with the true wine labels.
6. **Cluster Centroid Plot**: Visualize the clusters with their centroids in a 2D scatter plot.

## Features

- **Agglomerative Clustering**: Clusters wines into 3 distinct groups based on their features.
- **Dendrogram**: Visualizes the hierarchical clustering process.
- **Adjusted Rand Index (ARI)**: Evaluates the performance of the clustering model by comparing predicted clusters with true labels.
- **Cluster Centroid Plot**: Shows the centroid points of each cluster on a 2D plot.

## Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `scipy`

You can install the required libraries using:

```bash
pip install numpy pandas matplotlib scikit-learn scipy
```

## How to Run the Code

1. Clone this repository.
2. Install the necessary libraries (as mentioned above).
3. Run the Python script:

```bash
python hierarchical_clustering_wine.py
```

The script will:
- Load the Wine dataset
- Standardize the data
- Perform hierarchical clustering and plot the dendrogram
- Evaluate clustering performance using ARI
- Plot the clusters and centroids

## Results

The model’s performance is evaluated using:
- **Adjusted Rand Index (ARI)**: Measures clustering accuracy by comparing predicted clusters with true labels.

### Dendrogram Plot
The dendrogram shows the hierarchical relationships between wine samples. The color-coded branches represent different wine classes, making it easier to understand the clustering process.

### Cluster Centroid Plot
The cluster centroid plot displays the centroids of each cluster, offering insight into how the wine samples are grouped in a 2D space.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
