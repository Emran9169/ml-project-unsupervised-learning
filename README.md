# Wholesale Customer Segmentation Analysis

## Overview
This repository contains a comprehensive unsupervised learning project aimed at segmenting wholesale customers based on their annual spending in various product categories. The project encompasses data preprocessing, exploratory data analysis (EDA), principal component analysis (PCA), and clustering algorithms.
### Dataset
The dataset (Wholesale_Data.csv) refers to clients of a wholesale distributor and includes the following categories: Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicatessen.
### Project Structure and Steps
Data Preprocessing: Standardized the data and addressed any anomalies, ensuring a clean dataset for analysis.
Exploratory Data Analysis: Conducted initial analysis to understand the distribution and relationships of the features.
PCA: Applied Principal Component Analysis to reduce the dataset dimensionality while preserving the variance.
Clustering: Implemented KMeans and Hierarchical clustering to identify customer segments.
Interpretation and Strategy: Interpreted the clusters to define customer profiles and suggested strategic business actions.
### Analysis Summary
Exploratory Data Analysis: We visualized the distribution of each product category, noting significant skewness in the data. For instance, air plots were generated to observe bivariate relationships and identify potential correlations.
PCA Findings: PCA indicated that the first four components accounted for over 90% of the variance. The first component was heavily weighted by features associated with non-perishable products, while the second component was influenced by fresh food spending.
Clustering Outcomes: KMeans clustering suggested three customer segments, which were cross-validated with Hierarchical clustering. Both methods agreed on the optimal number of clusters, providing confidence in the stability of the segmentation.

