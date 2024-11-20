# CryptoClustering
## Introduction
 In this project we gonna predict if cryptocurrencies are affected by 24-hour or 7-day price changes
## Overview
Cryptocurrencies exhibit unique patterns in terms of price movements and market activity. This project:
Clusters cryptocurrencies using K-Means to identify distinct groups.
Compares clustering results between original and PCA-transformed data to assess the impact of dimensionality reduction.
Visualizes cluster distributions and key insights using hvPlot.
## Technologies Used
Libraries:
- pandas for data manipulation
- hvPlot for interactive visualizations
- scikit-learn for clustering and PCA
- StandardScaler for normalization

## Results
### Elbow Method:
Original Data: Optimal k = 4.
PCA-Reduced Data: Optimal k = 4.
### Cluster Analysis:
Identified groups of cryptocurrencies with similar behavior.
PCA allowed faster processing with minimal loss in clustering accuracy.

## Conclusion
This project demonstrates the application of K-Means and PCA to cluster cryptocurrencies effectively. Using PCA, dimensionality reduction simplifies the data without significantly impacting clustering results, providing a more efficient solution.

