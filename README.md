# Customer Segmentation using K-Means Clustering

![K-Means Clustering Visualization](https://i.imgur.com/JgV4DlA.png)

## Overview
This project demonstrates customer segmentation using the K-Means clustering algorithm on mall customer data. The analysis groups customers based on their annual income and spending score to identify distinct customer segments that can inform marketing strategies.

## Dataset
The dataset (`Mall_Customers.csv`) contains the following features for 200 customers:
- CustomerID 
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Methodology
1. **Data Preprocessing**: Selected relevant features (Annual Income and Spending Score)
2. **Optimal Cluster Selection**: Used the Elbow Method to determine the optimal number of clusters (k=5)
3. **K-Means Clustering**: Applied K-Means algorithm with k=5 clusters
4. **Visualization**: Created scatter plots to visualize the customer segments

## Key Findings
- Identified 5 distinct customer segments:
  1. High Income, Low Spending
  2. Moderate Income, Moderate Spending
  3. High Income, High Spending
  4. Low Income, High Spending
  5. Low Income, Low Spending
- The "High Income, High Spending" segment represents ideal target customers for premium products

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/customer-segmentation-kmeans.git
