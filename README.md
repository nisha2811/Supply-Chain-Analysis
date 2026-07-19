# Supply Chain Analytics & Late Delivery Prediction


# Project Overview

This project analyzes the **DataCo Supply Chain Dataset** to uncover operational inefficiencies, identify logistics bottlenecks, evaluate profitability, and predict late delivery risk using Machine Learning.
The project combines :-
- Business Analytics
- Machine Learning
- Data Visualization
- Geographic Analysis
- Forecasting
- Interactive Power BI Dashboard
It demonstrates a complete analytics workflow from **raw data to business insights and executive reporting.


# Business Objectives

The project aims to answer the following business questions:
- What percentage of deliveries are delayed?
- Which regions experience the highest delays?
- Which shipping modes contribute most to late deliveries?
- How do delays impact profitability?
- Which customer segments are most profitable?
- Can late deliveries be predicted before shipment?
- How healthy is the overall supply chain?


# Dataset

**Dataset:** DataCo Supply Chain Dataset

The dataset contains approximately **180,000+ supply chain transactions** across multiple countries and includes information such as :-
- Customer Details
- Product Information
- Order Information
- Shipping Details
- Delivery Status
- Profit Information
- Geographic Data

# Technologies Used

## Programming
- Python

## Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn
- XGBoost
- Prophet
- Imbalanced-Learn (SMOTE)
- Joblib

## Business Intelligence
- Power BI Desktop

# Project Workflow

## 1. Data Cleaning

Performed extensive preprocessing including:
- Removing redundant columns
- Removing personally identifiable information
- Handling missing values
- Date conversion
- Removing cancelled shipments
- Data validation

## 2. Feature Engineering

Created new business features:
- Order Processing Time
- Delivery Delay
- Is_Delayed
- Profitability Flag
- Order Month
- Order Day
- Order Hour
These engineered features improve both analysis and machine learning performance.

## 3. Exploratory Data Analysis (EDA)

Performed:
- Missing value analysis
- Duplicate detection
- KPI calculation
- Delay distribution
- Profitability distribution
- Order analysis
- Business metric generation

## 4. Profitability Analysis

Analyzed relationship between:
- Delivery delays
- Average profit
- Total profit
- Delay distribution
- Loss due to delayed deliveries

## 5. Bottleneck Detection

Identified operational bottlenecks using:
- Order Region
- Customer Segment
- Shipping Mode
- Department
- Order Status
- Order Type

## 6. Root Cause Analysis

Analyzed major causes of delayed deliveries by region.
Identified:
- High-risk shipping modes
- Departments causing delays
- Customer segment patterns
- Regional bottlenecks

## 7. Time-Based Analysis

Studied delivery performance across:
- Month
- Day of Week
- Hour of Day
to identify seasonal and operational trends.

## 8. Geographic Analysis

Performed regional analysis using:
- Delay Percentage by Region
- Country-wise Delay Heatmap
- Global Delivery Risk Map

## 9. Customer Insights

Analyzed:
- Customer profitability
- Delay rate by customer segment
- Customer clustering using K-Means
- Segment performance

## 10. Machine Learning

Built predictive models for late delivery prediction.


### Models

- Random Forest Classifier
- XGBoost Classifier


### Feature Engineering

- Frequency Encoding
- SMOTE Oversampling


### Target Variable

Late_delivery_risk


# Model Evaluation

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve
- ROC-AUC
- Confusion Matrix
Feature importance analysis was also performed to identify key drivers of late deliveries.


# Power BI Dashboard

An interactive **6-page Power BI Dashboard** was created to present business insights in a professional and user-friendly manner.

### Executive Dashboard

- Total Orders
- Late Deliveries
- Delay %
- Total Profit
- Supply Chain Health Score
- Monthly Delay Trend

### Delivery Performance Dashboard

- Delay % by Shipping Mode
- Delay % by Department
- Delay % by Region
- Delay % by Order Status
- Bottleneck Detection

### Geographic Analysis Dashboard

- Global Delay Heatmap
- Region-wise Delay Analysis
- Country Performance
- Regional KPIs

### Profitability Dashboard

- Delay vs Profit
- Profit by Region
- Delay Cost Analysis
- Revenue Impact
- Waterfall Analysis

### Customer Insights Dashboard

- Customer Segment Analysis
- Profitability by Segment
- Customer Clusters
- Delay Rate by Segment

### Machine Learning Dashboard

- Model Accuracy
- Precision
- Recall
- ROC-AUC
- Feature Importance
- Confusion Matrix
- ROC Curve
- Business Recommendations


# Key Business Insights

The analysis revealed several important findings :-
- Delivery delays significantly reduce overall profitability.
- Certain regions consistently experience higher delay percentages.
- Shipping mode is one of the strongest predictors of delivery delays.
- Customer profitability varies significantly across segments.
- Delay trends exhibit seasonal and hourly patterns.
- Machine learning models effectively identify high-risk deliveries before shipment.


# Business Recommendations

Based on the analysis :-
- Optimize high-delay shipping modes.
- Improve warehouse operations in high-risk regions.
- Prioritize high-risk orders identified by the prediction model.
- Monitor delay KPIs continuously through Power BI.
- Increase staffing during peak operational periods.
- Implement proactive shipment monitoring.


# Future Enhancements

Future improvements include:
- LightGBM Model
- CatBoost Model
- Hyperparameter Tuning
- Streamlit Web Application
- Real-Time Prediction API