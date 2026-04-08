Objective:
Segment customers based on purchasing behavior (Price & Quantity) to identify different buyer types.

Dataset:
Online Retail Dataset

Steps:

Data Cleaning:
Removed negative or zero values in Quantity and Price.
Feature Selection:
Selected numerical features: Price and Quantity.
Scaling:
Standardized features to ensure equal contribution to K-Means distance calculations.
Clustering:
Applied K-Means.
Determined optimal clusters (K = 3) using the Elbow method.
Results:
Cluster 1: Low price, low quantity → budget orders
Cluster 2: Low price, high quantity → bulk/wholesale orders
Cluster 3: High price, variable quantity → premium items
Outliers form separate clusters

Tech Stack:
Python | pandas | scikit-learn | matplotlib
