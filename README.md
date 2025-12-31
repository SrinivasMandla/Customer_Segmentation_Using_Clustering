# Customer_Segmentation_Using_Clustering
using python


Customer Segmentation Using Clustering (K-Means)
1. Project Overview

This project focuses on customer segmentation using K-Means clustering to analyze customer behavior and support data-driven marketing decisions.
Customers are grouped based on demographic and spending characteristics.

2. Project Objectives

Understand customer behavior using data analysis

Segment customers into meaningful groups

Provide insights for targeted marketing strategies

3. Dataset Description

Dataset: Mall Customers Dataset

Features Used:

Age

Annual Income (k$)

Spending Score (1–100)

4. Exploratory Data Analysis (EDA)

EDA is performed to understand the data before applying machine learning.

Steps Performed:

Checked for missing values and duplicates

Analyzed distributions of age, income, and spending score

Visualized relationships between income and spending

Compared spending patterns across gender

Key Insights:

Customers have varied spending behavior

Income alone does not determine spending

Patterns exist that are suitable for clustering

5. Feature Scaling

Applied StandardScaler to normalize features

Required because K-Means is distance-based

Prevents features with large values from dominating the model

6. Types of Clustering (Concept)

Clustering is an unsupervised learning technique.

Common clustering types:

K-Means Clustering

Hierarchical Clustering

DBSCAN

K-Means is chosen due to its simplicity and effectiveness for numeric customer data.

7. K-Means Clustering Method
Cluster Selection:

Elbow Method used to identify optimal number of clusters

Silhouette Score used to evaluate clustering quality

Algorithm Steps:

Initialize cluster centroids

Assign points to nearest centroid

Update centroids

Repeat until convergence

8. Dimensionality Reduction (PCA)

Applied Principal Component Analysis (PCA)

Reduced data to 2 dimensions

Used for clear visualization of clusters

9. Cluster Profiling

Each cluster is analyzed to convert data into business insights.

Profiling Includes:

Mean and median age

Mean and median income

Mean and median spending score

Customer count per cluster

Gender distribution

Purpose:
To understand who the customers are in each cluster.

10. Marketing Strategies Based on Clusters
Segment Type	Customer Behavior	Marketing Strategy
High Income – High Spending	Premium customers	Loyalty programs, exclusive offers
High Income – Low Spending	Untapped potential	Personalized discounts
Low Income – High Spending	Impulsive buyers	Flash sales, promotions
Low Income – Low Spending	Budget customers	Cost-effective offers
Young Moderate Spenders	Trend-focused	Social media marketing
