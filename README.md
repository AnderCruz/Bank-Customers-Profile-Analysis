# Bank Customer Segmentation Analysis

This project was developed by **Nowa Analytics Consulting** and is part of my professional portfolio designed to demonstrate applied data science capabilities in the financial sector.

## Project Overview

This notebook focuses on **customer segmentation** using behavioral data from **credit card users**. The aim is to identify distinct groups of customers based on their usage patterns to support targeted marketing strategies in the banking sector.

Using unsupervised machine learning, the project clusters customers into meaningful segments based on attributes such as spending behavior, payment patterns, credit limits, and cash advances.

## Dataset Summary

The dataset includes information about nearly 9,000 active credit card holders and 18 behavioral features:

* `CUSTID`: Customer identifier
* `BALANCE`: Account balance available for purchases
* `PURCHASES`, `ONEOFFPURCHASES`, `INSTALLMENTSPURCHASES`: Purchase behaviors
* `CASHADVANCE`: Cash withdrawn in advance
* `PURCHASESFREQUENCY`, `CASHADVANCEFREQUENCY`: Behavior frequencies
* `CREDITLIMIT`: Customer's credit limit
* `PAYMENTS`, `MINIMUM_PAYMENTS`: Payment behavior
* `PRCFULLPAYMENT`: Percentage of full payments made
* `TENURE`: Duration of the customer relationship

## Key Objectives

* Perform **data normalization** for clustering
* Apply **KMeans clustering** to group customers based on similar patterns
* Use **PCA (Principal Component Analysis)** to reduce dimensionality for visualization
* Support **banking decision-making** by identifying customer types for targeted campaigns

## Workflow Summary

1. **Data Loading & Cleaning**

   * Handled missing values and prepared the dataset for modeling.

2. **Normalization**

   * Standardized the data to ensure fair contribution of all variables in clustering.

3. **Dimensionality Reduction**

   * PCA was used to visualize and interpret high-dimensional data in 2D.

4. **Customer Segmentation**

   * KMeans clustering algorithm was applied.
   * Optimal number of clusters selected using the Elbow Method.

5. **Results Interpretation**

   * Cluster characteristics were analyzed to identify customer profiles.

## Key Insights

* Customers exhibit varying behaviors in usage, payments, and balance management.
* Clustering helps the bank personalize offerings such as loan limits, interest rates, or reward programs.
* The PCA plots provide a clear separation of segments.

## Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
