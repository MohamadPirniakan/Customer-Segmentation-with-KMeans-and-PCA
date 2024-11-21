# Customer Segmentation with KMeans and PCA

A comprehensive project for segmenting customers based on their credit card usage behavior. This project demonstrates the use of machine learning techniques for clustering, combined with robust data preprocessing and visualization.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Overview

Customer segmentation is an essential task for businesses to tailor their marketing strategies and improve customer satisfaction. This project uses KMeans clustering to segment customers based on their credit card behavior and visualizes the results using PCA for a better understanding of the clusters.

---

## Dataset

The dataset used in this project contains **18 behavioral features** of customers related to their credit card usage. The key steps in handling the dataset include:
- Handling missing values with **KNNImputer**.
- Managing outliers by creating range-based features.
- Normalizing the dataset for better clustering performance.

---

## Features

Key features of the dataset:
- **Numerical Attributes**: `BALANCE`, `PURCHASES`, `CREDIT_LIMIT`, etc.
- **Frequency Attributes**: `BALANCE_FREQUENCY`, `PURCHASES_FREQUENCY`, etc.
- **Categorical Features**: Converted from numerical ranges.

---

## Technologies Used

- **Python**: Programming language.
- **NumPy**: Numerical computations.
- **Pandas**: Data manipulation.
- **Scikit-learn**: Clustering and preprocessing.
- **Matplotlib/Seaborn**: Visualization.
- **KMeans**: Clustering algorithm.
- **PCA**: Dimensionality reduction for visualization.
- **Silhouette Analysis**: Evaluation of cluster quality.

---

## Project Workflow

1. **Data Preprocessing**:
   - Handling missing values using `KNNImputer`.
   - Scaling features with `StandardScaler`.
   - Converting outliers into categorical ranges.

2. **Clustering**:
   - Determining the optimal number of clusters using **Elbow Method**.
   - Evaluating clusters with **Silhouette Scores**.
   - Performing clustering using KMeans.

3. **Visualization**:
   - Reducing dimensions to 2D using PCA.
   - Visualizing clusters with distinct colors.

---

## Results

The project successfully segmented customers into **6 clusters** with the following characteristics:
1. **High Spenders**: Customers who make expensive purchases frequently.
2. **Installment Buyers**: Customers preferring installment-based purchases.
3. **Cash Advance Users**: Customers frequently taking cash advances.
4. **Low Spenders**: Customers with low overall spending.
5. **Irregular Users**: Customers with irregular usage patterns.
6. **Due Payment Customers**: Customers with higher outstanding payments.

Visualization of clusters helps in interpreting the behavior of different groups effectively.

---

## Usage

To run this project, follow these steps:

1. Clone the repository:
   ```bash
   https://github.com/MohamadPirniakan/Customer-Segmentation-with-KMeans-and-PCA.git
   cd customer-segmentation
