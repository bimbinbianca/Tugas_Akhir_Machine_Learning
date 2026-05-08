# ​Project Deep Dive: Bank Customer Churn & Segmentation

## ​Project Objective
​The primary goal of this project is to analyze customer transaction data to detect potential churn and perform in-depth segmentation. By understanding customer behavior, the bank can offer personalized products and services to enhance customer loyalty and retention.

## Data Preparation & Preprocessing
​To ensure high-quality analysis, I performed a rigorous End-to-End Data Lifecycle: 
- ​Data Collection & Cleaning: Addressed data integrity issues such as invalid inputs, duplicate records, and missing values caused by human error, system glitches, or potential security threats.
- ​Exploratory Data Analysis (EDA): Conducted deep-dive analysis to understand data distribution and relationships between customer occupations, transaction volumes, and churn patterns.
- ​Feature Scaling: Implemented Min-Max Scaling to normalize data values, ensuring more accurate results during the clustering process.

## Clustering Model Implementation
​I built a robust clustering model to validate customer distribution based on financial behavior:
- ​Elbow Method: Utilized this technique to determine the optimal number of clusters (k), ensuring the most balanced segmentation.
- ​K-Means Clustering: Applied the K-Means algorithm to group customers into distinct segments.
- ​Model Validation: Tested the results using the Silhouette Score to verify cluster validity and prevent issues such as overfitting or underfitting.

## Business Value
The model identifies customer segments based on:
- ​Occupation-based spending patterns.
- ​Transaction frequency and churn probability.
- ​Actionable insights for personalized banking product recommendations.

