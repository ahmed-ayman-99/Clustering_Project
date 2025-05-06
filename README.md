# Mall Customers Clustering Project

This project is part of my Data Mining training at ITI, where I explored customer segmentation using clustering techniques to understand spending patterns and enable more effective customer targeting for the business.

## 🎯 Goal

To segment mall customers into distinct groups based on their characteristics using K-Means Clustering. This analysis aims to provide insights into different customer segments, allowing the business to tailor marketing strategies and improve customer engagement.

## 💾 Dataset

The dataset used for this project is `Mall_Customers.csv`. It contains the following information about mall customers:

* **🧑‍💼 CustomerID:** Unique identifier for each customer.
* **🧍 Gender:** Gender of the customer.
* **🎂 Age:** Age of the customer.
* **💰 Annual Income (k$):** Annual income of the customer in thousands of dollars.
* **🛒 Spending Score (1–100):** A score assigned to the customer based on their spending behavior at the mall.

## 🛠️ Tools & Libraries

* **Python 🐍:** The primary programming language used for data analysis and model implementation.
* **Pandas 🧾:** A powerful library for data manipulation and analysis, providing efficient data structures like DataFrames.
* **Matplotlib & Seaborn 📊:** Libraries used for creating insightful visualizations to explore data and represent the clustering results.
* **Scikit-learn 🤖:** A comprehensive machine learning library in Python, used here for the K-Means clustering algorithm and data preprocessing.

## 📈 Key Steps

1.  **Data Exploration & Visualization:** Understanding the dataset through descriptive statistics and visualizing the distributions of different features and their relationships.
2.  **Data Preprocessing & Scaling:** Preparing the data for the clustering algorithm. This involved handling any missing values (if present) and scaling numerical features to ensure that no single feature dominates the distance calculations in K-Means.
3.  **Determining Optimal Number of Clusters:** Utilizing the **elbow method** to identify the optimal number of clusters (K) for the K-Means algorithm by analyzing the within-cluster sum of squares (WCSS) for different values of K.
4.  **K-Means Clustering:** Applying the K-Means algorithm with the determined optimal number of clusters to group the customers into distinct segments.
5.  **Cluster Visualization:** Visualizing the resulting customer clusters in relevant feature spaces (e.g., Annual Income vs. Spending Score) to understand the characteristics of each segment.
