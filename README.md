# Customer Churn Analysis - README

## Overview
This project analyzes customer churn in internet services and investigates how data correction affects model accuracy. The primary focus is on understanding the trade-offs between using raw data with outliers and data that has undergone outlier correction.

## Key Findings
- **Raw Data Results**: Using the raw customer churn dataset with outliers, the model achieved an accuracy of **100%**.
- **Treated Data Results**: After correcting for outliers, the model's accuracy reduced to **98%**.

## Conclusion
The analysis suggests that treating data and removing outliers may reduce the information available for the model to learn from, leading to a slight decrease in accuracy. While correcting outliers can improve data quality, it may sometimes lead to lower predictive power in machine learning models.

## Dataset
The dataset used in this project is the **Customer Churn Dataset** related to internet services. It contains various features used for predicting customer churn, and outliers were addressed during the data preprocessing phase.

## Dependencies
- Python
- Machine Learning libraries (scikit-learn, pandas, etc.)
- Data visualization tools

## Usage
The project can be used to understand the impact of data preprocessing on model performance, particularly in cases where data correction is necessary but may reduce model accuracy.
