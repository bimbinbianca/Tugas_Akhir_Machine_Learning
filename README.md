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

# ​Supervised Learning: Customer Churn Prediction
## Methodology
​The goal is to identify customers at risk of churn based on their demographic profile and financial behavioral patterns within the bank's database.
- ​Data Analysis: Instead of time-series data, the model analyzes key behavioral features such as account balance, product ownership, credit score, and activity status to determine the probability of a customer leaving.
- Feature Engineering: Conducted feature selection to identify which customer attributes are the strongest indicators of churn.
- Algorithms: Implemented and compared KNN, Random Forest, and SVM to build a robust classification system.

## ​Evaluation & Insights
- ​Metrics: Focused on Recall and F1-Score to ensure the model effectively captures as many potential churners as possible from the profile-based data.
- ​Outcome: Successfully created a classification model that segments customers into "At-Risk" and "Loyal" categories with high precision.

