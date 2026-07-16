# Suply-Chain-Project-Python

## Overview

This project analyzes supply chain operations using the DataCo Supply Chain Dataset.

The objective is to:

- Analyze delivery delays
- Measure profitability impact
- Detect logistics bottlenecks
- Identify root causes
- Predict late-delivery risk using Machine Learning


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)


## Project Workflow

### 1. Data Cleaning

- Remove redundant columns
- Handle date conversion
- Remove canceled shipments

### 2. Feature Engineering

Created:

- Order Processing Time
- Delay
- Is_Delayed
- Order Month
- Order Day
- Order Hour
- Profitability Flag

### 3. Exploratory Data Analysis

- Missing values analysis
- Distribution analysis
- KPI dashboard

### 4. Profitability Analysis

Study relationship between:

- Delivery delays
- Profitability

Metrics:

- Mean Profit
- Total Profit
- Delay Distribution

### 5. Bottleneck Detection

Analyze delay rates across:

- Regions
- Customer Segments
- Shipping Modes
- Departments

### 6. Root Cause Analysis

Top drivers of delay by region.

### 7. Time-Based Analysis

Delay trends by:

- Month
- Day of Week
- Hour

### 8. Machine Learning

Model: Random Forest Classifier

Techniques:

- Frequency Encoding
- SMOTE Balancing

Target:

Late_delivery_risk


## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score


## Business Value

This solution helps organizations:

- Reduce delivery delays
- Improve customer satisfaction
- Increase supply chain visibility
- Reduce operational risk
- Improve profitability


## Future Enhancements

- XGBoost
- LightGBM
- Feature Importance Analysis
- SHAP Explainability
- Real-time Prediction Dashboard