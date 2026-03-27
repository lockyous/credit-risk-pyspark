# Credit Risk Prediction with PySpark

This project builds a machine learning pipeline using PySpark to predict whether a loan applicant is likely to default. The model is first developed on a small dataset and then scaled to a distributed big data environment using GCP Dataproc.

## Problem
Credit risk prediction is an important task in the financial industry because accurate risk assessment directly affects lending decisions and financial stability.

## Dataset
Target Variable  
- Loan_Default_Status (1 = Default, 0 = Non-default)

Key Features  
- Customer_Age  
- Annual_Income  
- Credit_Score  
- Existing_Debt  
- Loan_Amount  
- Loan_Term_Months  
- Debt_to_Income_Ratio  
- Transaction_Behavior_Score  

## Technologies
- PySpark
- Python
- Google Colab
- Google Cloud Dataproc
- Machine Learning (Classification)

## Machine Learning Models
- Logistic Regression
- Random Forest

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

## Results

Small Dataset

Logistic Regression  
ROC AUC ≈ 0.919

Random Forest  
ROC AUC ≈ 0.903

Big Dataset

Logistic Regression  
ROC AUC ≈ 0.917

Random Forest  
ROC AUC ≈ 0.898

Logistic Regression performed slightly better than Random Forest on both datasets.

## Project Workflow
1. Data loading and exploratory analysis
2. Data preprocessing and missing value handling
3. Feature engineering
4. Model training and evaluation
5. Scaling the pipeline from small data to a distributed environment using GCP Dataproc

## Key Learning
This project demonstrates how machine learning pipelines can be scaled from small datasets to large distributed datasets using PySpark. It also highlights the importance of proper data preprocessing and type handling when working in distributed computing environments.
