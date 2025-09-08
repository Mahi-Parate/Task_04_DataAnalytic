Telecom Customer Churn Prediction:
Project Overview:

1.This project aims to predict customer churn for a telecom company using machine learning. Customer churn occurs when customers stop using a service, and predicting it helps businesses take proactive measures to retain customers.

2.The project uses Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn) to preprocess data, train models, and visualize insights.

Description: The dataset contains customer information, account details, services subscribed, charges, and churn labels.

Columns Include:

CustomerID, Gender, Senior Citizen, Partner, Dependents, Tenure Months

Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup

Device Protection, Tech Support, Streaming TV, Streaming Movies

Contract, Paperless Billing, Payment Method, Monthly Charges, Total Charges

Churn Label, Churn Value, Churn Score, CLTV, Churn Reason

Project Objectives:

1.Preprocess the dataset: handle missing values, encode categorical features, scale numerical features.

2.Train machine learning models to predict customer churn:

3.Logistic Regression

4.Random Forest Classifier

Classification Report

Visualize feature importance to understand which factors contribute most to churn.

Project Workflow:

Data Cleaning & Preprocessing: remove irrelevant columns, handle missing values, encode categorical variables, scale numeric features.

Data Splitting: split dataset into training and testing sets (stratified to preserve class distribution).

Model Training: train Logistic Regression and Random Forest Classifier.

Evaluation & Visualization: calculate metrics, plot confusion matrix, visualize feature importance.

Model Saving: export models using Joblib for deployment.

Results

1.Random Forest achieved high accuracy and ROC-AUC score, making it the best model for churn prediction.

2.Feature importance highlighted key drivers like Tenure Months, Monthly Charges, Contract Type, and Tech Support.
