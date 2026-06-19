# Customer Segmentation Using K-Means Clustering (SCT_ML_2)

## Project Overview
This project implements an Unsupervised Machine Learning model using the K-Means Clustering algorithm. The goal is to group and segment customers of a retail shop based on their mutual purchasing habits, specifically focusing on their Annual Income and Spending Score.

## Dataset
- **Source:** Kaggle Mall Customers Dataset (`Mall_Customers.csv`)
- **Features Used:** Annual Income (k$) and Spending Score (1-100)

## Methodology
1. **The Elbow Method:** Used to calculate the Within-Cluster Sum of Squares (WCSS) to find the optimal number of clusters (which clearly shows an "elbow" bend at 5 clusters).
2. **K-Means Model:** Trained with 5 clusters to segment the data.
3. **Visualization:** Plotted a 2D scatter plot displaying the 5 distinct consumer groups along with their centroids.

## Key Insights / Customer Groups Found
- Cluster 1: High Income, Low Spending (Careful)
- Cluster 2: Average Income, Average Spending (Standard)
- Cluster 3: High Income, High Spending (Target Group)
- Cluster 4: Low Income, High Spending (Spendthrift)
- Cluster 5: Low Income, Low Spending (Sensible)

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, scikit-learn
