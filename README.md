# Customer Segmentation with K-Means Clustering

## 📌 Project Overview
This project focuses on Customer Segmentation using K-Means Clustering. The goal is to group customers based on their purchasing behavior and demographic attributes. Clustering helps businesses in targeted marketing strategies.

## 📊 Dataset Information

The dataset contains customer information such as Gender, Age, Annual Income, and Spending Score.

The data is preprocessed before applying clustering.

The Gender column is retained but excluded from correlation analysis to avoid skewed results.

## 🔧 Implementation Steps

1. Import Libraries: Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

2. Load Dataset: Read the customer data into a Pandas DataFrame.

3. Data Cleaning & Preprocessing:

         Handle missing values (if any).
         Convert categorical data where necessary.
         Normalize or scale data if required.

4. Exploratory Data Analysis (EDA):

         Visualize income distribution, spending habits, and other patterns.
         Compute the correlation matrix (excluding categorical variables like Gender).

5. Apply K-Means Clustering:

         Determine the optimal number of clusters using the Elbow Method.
         Fit the K-Means model and assign cluster labels.

6. Visualize the Results:

         Scatter plots to visualize customer segments.
         Heatmaps for correlation analysis.
