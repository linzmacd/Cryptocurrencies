# Cryptocurrency Analysis

## Purpose

The purpose of this project was to use unsupervised computer learning to design a classification system for cryptocurrency based on total coins mined, total coin supply, proof type, and algorithm.

## Methods

We preprocessed and standardized the data set for PCA, reducing the dimensions down to three principal components. We then created an elbow curve to find the optimal number of clusters to look for using the K-means model. After running the model with K=4, we visualized the results in a 3D scatter plot of the classes across the three principal components and a 2D scatter plot of scaled values of total coins mined vs. scaled total coin supply. 