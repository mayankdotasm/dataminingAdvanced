# Practical Assignment 1: Clustering

## Overview
This assignment explores various clustering algorithms, including Simple K-means, Hierarchical Agglomerative Clustering, and DBSCAN. The objective is to evaluate their performance by analyzing clustering metrics and visualizations using different datasets. 

## Datasets
- **Iris Dataset** 
- **Dry Bean Dataset**
- **Wine Dataset**

## Objectives
1. **Simple K-means Clustering**:
    - Apply the Simple K-means algorithm on any of the selected datasets.
    - Compare the performance of clusters by changing initialization parameters:
        - Random (`rand`)
        - K-means++ (`kmeans++`)
        - Fixed initialization (`fixed`)
    - Evaluate clustering performance using:
        - Sum of Squared Errors (SSE)
        - Weighted Purity

2. **Hierarchical Agglomerative Clustering**:
    - Apply Hierarchical Agglomerative Clustering on the selected dataset.
    - Plot the dendrogram to visualize the clustering process.
    - Determine the desired number of clusters based on the total class labels.
    - Compute the following supervised evaluation metrics:
        - Entropy
        - Weighted Purity
        - Precision
        - Recall
        - F-measure

3. **DBSCAN Clustering**:
    - Apply DBSCAN on a dataset with class labels.
    - Plot F-measure for different values of epsilon (ε) to analyze its impact on the clustering scheme.
    - Vary the minimum points parameter and observe the change in weighted purity, displaying results in a bar plot.
    - Display the number of outliers detected in each case.

4. **Comparison of Clustering Algorithms**:
    - Compare the clustering output of K-means, Agglomerative, and DBSCAN using a bar plot.
    - Ensure to consider optimal parameter settings for each algorithm.

## Installation
To run the code and generate the required outputs, ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
