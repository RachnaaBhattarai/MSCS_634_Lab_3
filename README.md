# MSCS_634_Lab_3

# Lab 3: Clustering Analysis Using K-Means and K-Medoids Algorithms

## Course: MSCS 634 - Advanced Big Data and Data Mining (Summer 2025)  
**Name:** Rachna Bhattarai 
**Date:** June 7, 2025

## Purpose

This lab aims to explore unsupervised learning techniques by applying K-Means and K-Medoids clustering algorithms to the Wine dataset from the sklearn library. The task involves analyzing cluster quality through visualization and performance metrics—Silhouette Score and Adjusted Rand Index (ARI)—to understand how well the models group data based on chemical features. This lab provides practical experience in evaluating and comparing clustering methods on real-world data.

## Key Insights and Observations

The K-Means algorithm produced better-defined clusters, yielding a **Silhouette Score of 0.285** and an **ARI of 0.897**, indicating high alignment with actual labels. In contrast, K-Medoids gave a **Silhouette Score of 0.266** and an **ARI of 0.726**, slightly underperforming in cluster coherence. However, K-Medoids showed robustness to outliers since medoids are actual data points, not means. Visualizations showed K-Means clusters as tighter and more separable, while K-Medoids was more stable under noise.

## Challenges and Decisions

A challenge faced was the `ModuleNotFoundError` for `sklearn_extra`, which was resolved by installing the `scikit-learn-extra` package. . The decision to normalize the dataset ensured features had equal weight in clustering. Overall, K-Means was preferred for its efficiency and clean separation, while K-Medoids would be favored in scenarios sensitive to noise or outliers.
