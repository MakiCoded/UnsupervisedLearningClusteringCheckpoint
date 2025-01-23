# Credit Card Dataset Clustering

This Jupyter Notebook demonstrates the process of clustering a credit card dataset using both hierarchical clustering and K-means clustering. The notebook includes data exploration, data preparation, and visualization of the clustering results.

## Table of Contents

1. [Basic Data Exploration](#basic-data-exploration)
2. [Data Preparation](#data-preparation)
    - [Handling Missing Values](#handling-missing-values)
    - [Handling Outliers](#handling-outliers)
    - [Feature Scaling](#feature-scaling)
3. [Clustering](#clustering)
    - [Hierarchical Clustering](#hierarchical-clustering)
    - [K-means Clustering](#k-means-clustering)
    - [Finding the Best k Value](#finding-the-best-k-value)
    - [Re-plotting with the Best k Value](#re-plotting-with-the-best-k-value)
4. [Interpretation of Results](#interpretation-of-results)

## Basic Data Exploration

We start by loading the dataset and performing basic data exploration to understand the structure and summary statistics of the data.

## Data Preparation

### Handling Missing Values

We handle missing values by dropping rows with any missing values.

### Handling Outliers

We handle outliers in the `PURCHASES` and `CREDIT_LIMIT` columns using the IQR method.

### Feature Scaling

We scale the features `PURCHASES` and `CREDIT_LIMIT` using `StandardScaler` to normalize the data.

## Clustering

### Hierarchical Clustering

We perform hierarchical clustering using the Ward method and visualize the results with a dendrogram.

### K-means Clustering

We perform K-means clustering with an initial guess of 3 clusters and visualize the results.

### Finding the Best k Value

We use the elbow method to find the optimal number of clusters (k) by plotting the inertia for different values of k.

### Re-plotting with the Best k Value

We re-plot the K-means clustering results using the optimal k value determined from the elbow plot.

## Interpretation of Results

We interpret the clustering results by examining the mean values of the features for each cluster.

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- scikit-learn
- scipy
- matplotlib

## Usage

1. Clone the repository.
2. Install the required packages.
3. Open the Jupyter Notebook and run the cells sequentially.

## License

This project is licensed under the MIT License.

##  Created By Macdonald Osakwe
