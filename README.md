# Data-mining-Tasks
 This repository contains various tasks related to data mining techniques, including data preprocessing, association rules mining, classification, and clustering. The tasks cover fundamental operations such as calculating central tendencies, generating visualizations, discretizing and normalizing data, implementing association rules, and applying KNN and K-means algorithms.

## Directory Structure

Each task is organized in its own folder (`tp1`, `tp2`, `tp3`, ..., `tp6`).


## Overview of Tasks

### TP1 - Data Exploration
1. **Load Dataset**: Write a function to load the dataset.
2. **Display Basic Information**: Write a function to display basic dataset information.
3. **Calculate Central Tendencies**: Write a function to calculate the central tendencies of an attribute.
4. **Quartiles Calculation**: Write a function to calculate the quartiles (Q0, Q1, Q2, Q3, Q4) of an attribute.
5. **Missing Values**: Write a function to display the number and percentage of missing values for an attribute.
6. **Unique Values**: Write a function to display the number of unique values for an attribute.

### TP2 - Data Visualization
1. **Scatter Plot**: Write a function to generate a scatter plot for a pair of attributes.
2. **Histogram/Bar Chart**: Write a function to generate a histogram (and bar chart) for an attribute.
3. **Box Plot**: Write a function to generate a box plot for an attribute, both with and without outliers.

### TP3 - Data Preprocessing
1. **Discretization**: Discretize the values of the dataset using equal-width intervals (Method 2).
2. **Replace Discretized Values**: Replace the discretized values with the average of the corresponding interval.
3. **Normalization**: Normalize the values of the dataset using Method 1 (Min-Max normalization).

### TP4 - Association Rules and Apriori Algorithm
1. **Generate k-Itemset Candidates**: Write a function to generate the k-itemset candidates `Ck`.
2. **Support Calculation**: Write a function to calculate the support of the k-itemsets `Ck`.
3. **Generate Frequent k-Itemsets**: Write a function to generate the frequent k-itemsets `Lk`.
4. **Generate Association Rules**: Write a function to generate all the association rules of a `Lk`.
5. **Calculate Confidence**: Write a function to calculate the confidence of an association rule.

### TP5 - KNN Classification
1. **Distance Function**: Write a function to calculate the distance between two instances of the dataset using Manhattan and Hamming distances.
2. **Sort Instances**: Write a function to sort the instances of the dataset according to the calculated distance.
3. **Dominant Class**: Write a function to return the dominant class among a set of `K` classes.
4. **KNN Algorithm**: Implement the K-Nearest Neighbors (KNN) algorithm.
5. **Class Prediction**: Deduce the class of a new instance using K = 3 and K = 10.

### TP6 - K-Means Clustering
1. **Reuse Distance Function**: Re-use the distance function from TP5.
2. **Centroid Calculation**: Write a function to calculate the centroid of a set of instances.
3. **Cluster Assignment**: Write a function to find the cluster to which a given instance is closest.
4. **K-Means Algorithm**: Implement the K-Means clustering algorithm.
5. **Clustering Results**: Test the algorithm with k = 2, k = 5, and k = 6. Provide an interpretation of the obtained clustering.

## How to Use

1. **Clone the Repository**:  
   Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Ken0uz/Data-mining-Tasks

