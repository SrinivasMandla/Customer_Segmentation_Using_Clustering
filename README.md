# Customer_Segmentation_Using_Clustering
using python
Customer Segmentation Using Clustering (K-Means)

This project focuses on segmenting customers using K-Means clustering to understand customer behavior and support data-driven marketing strategies.
The analysis uses demographic and spending data to identify distinct customer groups.

Project Objectives

Understand customer behavior using data analysis

Group customers into meaningful segments

Support targeted marketing and business decisions

Dataset

Mall Customers Dataset

Features used:

Age

Annual Income (k$)

Spending Score (1–100)

Exploratory Data Analysis (EDA)

EDA is performed to understand data distribution and relationships before modeling.

EDA Steps:

Checked for missing values and duplicates

Analyzed feature distributions:

Age

Annual Income

Spending Score

Visualized relationships between income and spending

Compared spending behavior by gender

Insights from EDA:

Customers show diverse spending behaviors

Income alone does not define spending habits

Clear patterns exist that can be leveraged for clustering

Feature Scaling

Since clustering is distance-based:

StandardScaler is applied to normalize features

Ensures fair contribution of all variables during clustering

Clustering Techniques (Types)

Clustering is an unsupervised learning technique.

Common Types of Clustering:

K-Means Clustering (used in this project)

Hierarchical Clustering

DBSCAN

Why K-Means?

Simple and efficient

Works well with numeric data

Suitable for customer segmentation problems

K-Means Clustering
Model Selection:

Elbow Method used to find optimal number of clusters

Silhouette Score used to validate cluster quality

Final k chosen based on highest silhouette score

Process:

Initialize cluster centers

Assign data points to nearest cluster

Update centroids

Repeat until convergence

Dimensionality Reduction (PCA)

Principal Component Analysis (PCA) reduces data to 2 dimensions

Helps visualize clusters clearly

Preserves maximum variance in data

Cluster Profiling

After clustering, each group is analyzed to understand its characteristics.

Profiling Metrics:

Average and median age

Average and median income

Average and median spending score

Customer count per cluster

Gender distribution

Purpose:

Convert raw clusters into business-understandable segments

Identify high-value and low-value customer groups

Marketing Strategies Based on Clusters
Customer Segment	Characteristics	Suggested Strategy
High Income – High Spending	Premium customers	Loyalty programs, exclusive offers
High Income – Low Spending	Potential customers	Personalized promotions
Low Income – High Spending	Impulsive buyers	Discounts, limited-time deals
Low Income – Low Spending	Budget customers	Basic offers, cost-effective products
Young Moderate Spenders	Trend-driven	Social media & influencer marketing
