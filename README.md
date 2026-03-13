# Customer Segmentation using K-Means Clustering

This project applies **unsupervised machine learning** to segment customers based on purchasing behavior.

The goal is to identify meaningful customer groups that businesses can target with different marketing strategies.

---

## Project Overview

Customer segmentation is widely used in marketing and retail to understand different customer behaviors.

In this project we:

- Preprocessed transactional customer data
- Selected behavioral features
- Scaled features using StandardScaler
- Applied **K-Means clustering**
- Determined optimal clusters using the **Elbow Method**
- Evaluated clustering quality using **Silhouette Score**

---

## Dataset Features

The clustering was performed using the following features:

- Recency
- Frequency
- Monetary Value
- Quantity

These features represent customer purchasing patterns.

---

## Clustering Visualization

Below is a visualization of the identified customer segments.

![Customer Segmentation](images/cluster_visualization.png)

Each color represents a different cluster of customers.

---

## Cluster Interpretation

| Cluster | Description |
|-------|-------------|
| Cluster 0 | Low-value customers |
| Cluster 1 | Occasional buyers |
| Cluster 2 | Loyal customers |
| Cluster 3 | High-value / VIP customers |

These segments help businesses design targeted marketing strategies.

---

## Evaluation

Clustering quality was evaluated using **Silhouette Score**.
