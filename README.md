# Telco Customer Churn Analysis

# Project Overview

This project focuses on analyzing customer churn behavior in a telecom company using Exploratory Data Analysis (EDA). The objective of the analysis is to identify the major factors influencing customer churn and provide actionable business insights that can help improve customer retention strategies.
The analysis was performed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn within Jupyter Notebook.

# Objectives

- Analyze overall customer churn trends
- Identify demographic factors affecting churn
- Understand the impact of services and contract types on churn
- Analyze customer tenure and payment behavior
- Generate business recommendations to reduce customer churn

# Dataset Information
The dataset contains telecom customer information, including:

- Customer demographics
- Internet services
- Contract types
- Payment methods
- Monthly and total charges
- Customer churn status

# Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

# Data Cleaning & Preprocessing
The following preprocessing steps were performed:

- Checked for missing values
- Converted data types
- Cleaned invalid entries in TotalCharges
- Created visualizations for churn analysis
- Performed categorical feature analysis

# Key Insights

## Overall Churn Rate

- The customer churn rate is 26.54%, while 73.46% of customers were retained.

## Demographic Insights

- Senior citizens showed a higher churn rate (30%) compared to non-senior customers (24%).
- Gender had minimal impact on churn behavior.

## Service-Based Insights

- Customers without services like OnlineSecurity, TechSupport, and DeviceProtection showed significantly higher churn rates.
- Customers using Fiber Optic internet service had a higher churn rate compared to DSL users.

## Contract & Tenure Insights

- Customers with monthly contracts had much higher churn rates than yearly contract users.
- Customers with shorter tenure periods were more likely to churn.

## Payment Method Insights

- Customers using Electronic Check payment methods showed the highest churn percentage.

# Visualizations Included
The project contains multiple visualizations, including:

- Churn Distribution Countplots
- Pie Charts
- Stacked Bar Charts
- Histogram Analysis
- Contract-wise Churn Analysis
- Payment Method Comparison
- Service-wise Churn Comparisons

# Business Recommendations
Based on the analysis, the following strategies are recommended:

- Encourage customers to move from monthly to yearly contracts
- Promote value-added services such as TechSupport and OnlineSecurity
- Create targeted retention programs for senior citizens
- Improve customer support for Fiber Optic users
- Optimize payment options and customer engagement strategies

# Conclusion
This project demonstrates how Exploratory Data Analysis can be used to uncover important customer behavior patterns and business risks. The insights generated from this analysis can help telecom companies improve customer retention, reduce churn rates, and develop more effective customer engagement strategies.

# How to Run the Project

1. Clone the repository
2. Install required libraries:

pip install pandas numpy matplotlib seaborn

3. Open the Jupyter Notebook
4. Run all cells sequentially

# Project Structure

├── Dataset/
├── Notebook/
├── Summary/
├── README.md
