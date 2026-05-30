# Bank Customer Churn Analysis Dashboard

## Overview

This project provides a comprehensive analysis of a banking customer dataset using Power BI, exploratory data analysis, and business intelligence techniques.

The objective is to understand customer churn behavior, identify factors influencing customer retention, and support data-driven decision-making through interactive visualizations and key performance indicators.

---

## Objectives

* Analyze customer churn distribution and trends
* Understand customer demographics and behavior
* Evaluate customer financial activity
* Identify high-risk customer segments
* Analyze the impact of customer tenure on churn
* Support customer retention strategies through data insights

---

## Tools and Technologies

* Power BI
* DAX
* Power Query
* Excel
* Data Visualization
* Jupyter Notebook
* Python (Pandas, NumPy)

---

## Dataset Description

The dataset contains banking customer information including:

* Customer ID
* Age
* Occupation
* Current Balance
* Debit Transactions
* Credit Transactions
* Customer Vintage (Tenure)
* Net Worth Category
* Churn Status

The dataset was cleaned and transformed to support customer churn analysis and business intelligence reporting.

---

## Data Preprocessing

### Data Cleaning

* Removed duplicate records
* Handled missing values
* Standardized column names
* Corrected data types
* Validated data consistency

### Feature Analysis

The analysis focused on key customer attributes including:

* Age
* Occupation
* Account Balance
* Debit Activity
* Credit Activity
* Customer Vintage
* Net Worth Category
* Churn Status

---

## Exploratory Data Analysis

The analysis includes:

* Customer churn distribution
* Customer age distribution
* Occupation-based churn analysis
* Net-worth category analysis
* Debit vs Credit transaction trends
* Customer balance analysis
* Customer tenure (Vintage) analysis

---

## Dashboard Description

### 1. Executive Overview

Provides a high-level summary of:

* Total Customers
* Total Churned Customers
* Churn Rate

### 2. Customer Churn Analysis

Visualizes:

* Customer churn distribution
* Churn percentage
* Occupation-based churn analysis

### 3. Customer Demographics

Includes:

* Age distribution
* Customer segmentation
* Occupation analysis

### 4. Financial Behavior Analysis

Displays:

* Average balance by churn status
* Debit vs Credit transaction trends
* Customer financial activity patterns

### 5. Customer Retention Insights

Analyzes:

* Customer vintage impact on churn
* Net-worth category distribution
* High-risk customer segments

---

## Dashboard Preview

### Bank Customer Churn Dashboard

![Dashboard](images/dashboard_preview.png)

---

## Key Insights

* Customers with lower balances tend to exhibit higher churn rates.
* Customer occupation influences churn behavior.
* Long-term customers generally show higher retention rates.
* Transaction activity patterns differ between churned and retained customers.
* Customer demographics play an important role in churn analysis.

---

## Recommendations

* Develop targeted retention campaigns for high-risk customers.
* Monitor customer transaction activity regularly.
* Improve customer engagement programs.
* Offer personalized services based on customer profiles.
* Use predictive analytics to identify potential churn risks.

---

## Project Structure

```text
Bank-Customer-Churn-Analysis/
│
├── notebook/
│   └── final_data_analysis (1).ipynb
│
├── Dashboard/
│   └── Bank Customer Churn Dashboard.pbix
│
├── data/
│   └── churn_prediction_Cleaned.csv
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## How to Run the Project

1. Open the notebook:

   notebook/final_data_analysis (1).ipynb

2. Run all cells to:

   * Clean and preprocess data
   * Perform exploratory data analysis
   * Generate business insights

3. Open the Power BI dashboard:

   Dashboard/Bank Customer Churn Dashboard.pbix

4. Refresh the dataset if required.

5. Interact with filters and visualizations to explore customer churn patterns.

---

## Future Improvements

* Build machine learning models for churn prediction.
* Integrate real-time banking data.
* Implement customer segmentation models.
* Add predictive analytics features.
* Deploy dashboards using Power BI Service.

---

## Author

**Sara Essam**
