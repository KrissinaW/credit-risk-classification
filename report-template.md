# Module 20 Report

# Overview of the Analysis

## * Purpose of the Analysis:

The purpose of this analysis was to develop and evaluate machine learning models to predict the risk associated with loan applications. Specifically, the goal was to classify loans as either healthy (low-risk) or high-risk based on various financial indicators.

## * Financial Information and Prediction
The dataset used for this analysis contains financial information related to loan applications, including various features that describe the financial status of the applicants and the terms of the loans. The primary task was to predict whether a loan would be classified as 0 (healthy loan) or 1 (high-risk loan).

## * Machine Learning Process
Data Preparation: Loaded and cleaned the dataset, ensuring that all necessary features were available and appropriately formatted.
Feature Selection: Selected relevant features for model training.
Model Training: Trained several machine learning models, including logistic regression and decision tree classifiers.
Model Evaluation: Evaluated the performance of each model using accuracy, precision, recall, and F1-score metrics.

## * Methods Used
Logistic Regression: Used for its simplicity and effectiveness in binary classification tasks.

# Results

Machine Learning : Logistic Regression

Accuracy: 0.99

Precision:
Class 0: 1.00
Class 1: 0.85

Recall:
Class 0: 0.99
Class 1: 0.91

F1-Score:
Class 0: 1.00
Class 1: 0.88


# Summary

## Model Performance

### Logistic Regression:

#### Strengths: Excellent overall performance with near-perfect precision and recall for healthy loans. It also maintains good performance for high-risk loans with an F1-score of 0.88.

#### Weaknesses: Slightly lower precision for high-risk loans, meaning some healthy loans may be incorrectly classified as high-risk.

# Recommendation

Based on the evaluation metrics, the Logistic Regression model is recommended for deployment. It performs best overall, especially in predicting healthy loans with near-perfect metrics, and maintains good performance in predicting high-risk loans. This balance is crucial for minimizing financial risk while maintaining a high level of accuracy.

# Performance Consideration

## Importance of Predicting High-Risk Loans: If predicting high-risk loans (1) is more critical due to potential financial losses, the slight improvement in recall (0.91) with logistic regression is beneficial.

## Overall Balance: Logistic regression offers a better balance between precision and recall across both classes, making it a reliable choice for deployment in a loans application approval system.

If further refinement is needed, considering additional features or methods could enhance the model's performance.
