# SmartCart-e-commerce


# SmartCart Customer Segmentation System

## Problem Statement

SmartCart is a growing e-commerce platform operating across multiple countries with over 2,000 customer records and detailed behavioral data.

Currently, the company applies **generic marketing strategies** to all customers without understanding different behavioral patterns. This results in:

* Inefficient marketing spend
* Poor personalization
* Missed opportunities to retain high-value customers
* Delayed identification of churn-prone users

The objective of this project is to build an **Intelligent Customer Segmentation System** using **unsupervised machine learning** to discover hidden patterns in customer behavior and group customers into meaningful segments.

---

## Dataset Overview

The dataset contains **2240 customer records** and includes:

###  Customer Demographics

* Year of birth
* Education level
* Marital status
* Income
* Number of children
* Customer enrollment date

###  Purchase Behavior (Spending)

* Spending across 6 product categories
* Total spending derived feature

###  Purchase Behavior (Frequency)

* Web purchases
* Store purchases
* Catalog purchases
* Discount purchases
* Monthly website visits

###  Engagement Indicators

* Recency (days since last purchase)
* Campaign response
* Complaint history

###  Engineered Features

* Age
* Customer tenure
* Total spending
* Total children
* Encoded categorical variables

The data was cleaned, scaled, transformed using PCA, and clustered using K-Means and Agglomerative Clustering.

---

##  Methodology

1. Data Cleaning & Missing Value Treatment
2. Feature Engineering
3. One-Hot Encoding for Categorical Variables
4. Standardization of Features
5. Dimensionality Reduction using PCA
6. Optimal Cluster Selection (Elbow Method + Silhouette Score)
7. Clustering using:

   * K-Means
   * Agglomerative Clustering

Final segmentation was performed using 4 clusters.

---

##  Customer Segments Identified

###  Cluster 0 (Red Cluster)– Budget-Conscious Family Shoppers

Low to moderate income, higher number of children, high browsing activity but lower purchase conversion. Price-sensitive segment.

###  Cluster 1 (Blue Cluster)– Affluent Traditional Buyers

High income and spending, prefer store purchases, stable and premium customer base.

###  Cluster 2 (Yellow Cluster)– Digital Browsers

Low income and low spending, high web visits but minimal purchases. Potential retargeting segment.

###  Cluster 3 (Green Cluster)– High-Value Engaged Customers

High spending, strong campaign responsiveness, high web and store purchases. Most valuable segment.

---

##  Business Impact

This segmentation system enables SmartCart to:

* Replace generic marketing with targeted strategies
* Improve marketing ROI
* Identify premium and price-sensitive groups
* Increase customer retention
* Personalize campaigns based on behavioral patterns

The project demonstrates how unsupervised learning can transform raw transactional data into actionable business insights.
