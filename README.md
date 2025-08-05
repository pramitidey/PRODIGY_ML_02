# 🧠 Customer Segmentation using K-Means 

This project applies unsupervised machine learning — specifically **K-Means Clustering**  for **customer segmentation** — to segment customers based on their purchasing behavior and demographics. The objective is to identify distinct groups of customers to help businesses tailor their marketing strategies effectively.

## Goal
 The goal of this project is to group customers into distinct segments based on their behavior and characteristics, which can then be used to tailor marketing strategies, product recommendations, and more.

## 📊 Problem Statement

In modern business, understanding customer behavior is crucial for targeted marketing, improved customer satisfaction, and increased revenue. Using clustering algorithms, we can uncover hidden patterns and group customers based on similarities in their behavior and characteristics.

## Table of Contents
- [Project Overview](#project-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Visualization](#visualization)
- [Technologies Used](#technologies-used)
- [Conclusion](#conclusion)

## 🚀 Project Overview
Customer segmentation is a crucial task in various industries, allowing businesses to understand their customer base and target specific groups more effectively. This project leverages the K-means clustering algorithm to segment customers based on key features.

The project is divided into three main phases:

1. **Exploratory Data Analysis (EDA):** Analyzing the dataset to understand the distribution and relationships of features.

2. **Modeling:** Applying the K-means algorithm and selecting the optimal number of clusters using inertia and silhouette score.

3. **Visualization:** Visualizing the clusters and their centroids using 2D and 3D scatter plots.

## Exploratory Data Analysis (EDA)

EDA is the initial phase of the project, where we explored the dataset to gain insights into the distribution and relationships of the features. Several visualization techniques were used:

- **Histograms & KDE Plots:** To analyze the distribution of numerical features.

- **Pair Plots:** To visualize relationships between features.

- **Swarm & Violin Plots:** To understand the distribution of data across categories.

- **Lmplot:** To fit linear models and visualize relationships.

These plots helped in identifying patterns and potential correlations in the data, which informed the choice of features for clustering.

## Modeling

After understanding the data, the K-means clustering algorithm was applied. The following steps were taken:

1. **Segmanting Data:** The dataset was segmented based on customer features we want to cluster

2. **Inertia Calculation:** Inertia was calculated for various values of k (number of clusters) to assess how well the algorithm is clustering the data.

3. **Silhouette Score Calculation:** Silhouette scores were computed for different values of k to measure how similar each point is to its own cluster compared to other clusters.

4. **Choosing the Optimal k:** Interactive line plots were used to visualize both inertia and silhouette scores for different k values, helping to select the optimal number of clusters.

## Visualization
Once the optimal k was determined, the final customer groups were visualized using:

- **Interactive Scatter Plot:** A 2D scatter plot displaying each customer group and its corresponding centroid.

- **Interactive 3D Scatter Plot:** A 3D plot for better visualization of clusters in higher-dimensional space.

## Technologies Used
- **Python:** The programming language used for the entire project.

- **Pandas:** For data manipulation and preprocessing.

- **Seaborn & Matplotlib:** For data visualization during the EDA phase.

- **Plotly:** For creating interactive plots (2D and 3D scatter plots, line plots).

- **Scikit-learn:** For implementing the K-means clustering algorithm and evaluating the model using inertia and silhouette scores.

## Conclusion
This project successfully demonstrates the process of customer segmentation using the K-means clustering algorithm
