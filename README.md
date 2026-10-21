# Telecom Customer Churn Prediction

## Project Overview 

Customer churn is a key business challenge for telecommunications companies, leading to lost recurring revenue and reduced customer lifetime value. Identifying customers at risk of leaving can help move from reactive retention efforts to more targeted, proactive interventions.

This project uses exploratory data analysis and machine learning models to identify churn patterns, predict customer attrition, and inform targeted retention strategies.

## Business Problem

The business needs to identify which customers are most likely to leave, understand the factors associated with churn, and execute retention efforts accordingly. Without a reliable way to assess customer risk, retention campaigns may be applied too broadly, wasting resources on customers who are unlikely to leave while missing those who need intervention.

This project addresses the problem by comparing classification models to predict customer churn, evaluating their performance, and identifying higher-risk customer groups to support targeted retention strategies.

## Project Approach

- **Exploratory Data Analysis:** Examined customer usage, charges, service interactions and account characteristics to identify patterns associated with churn.
- **Data Preparation:** Assessed data quality, standardised numerical features and prepared training and test datasets.
- **Predictive Modelling:** Built and compared Logistic Regression, Random Forest and XGBoost classification models using accuracy, precision, recall, F1-score and ROC-AUC.
- **Model Interpretation & Risk Segmentation:** Used feature importance, odds ratios and SHAP analysis to interpret model predictions and identify higher-risk customer groups.
- **Business Recommendations:** Translated the findings into actionable retention strategies, including proactive contract renewal, targeted plan recommendations and risk-based customer service interventions, to help identify at-risk customers.
