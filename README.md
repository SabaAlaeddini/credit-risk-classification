# credit-risk-classification
Module 20 Challenge
# Credit Risk Analysis with Logistic Regression
# Overview
This project applies Logistic Regression to assess credit risk by predicting whether loans are healthy (0) or high-risk (1). The goal is to evaluate the model’s effectiveness in classifying loan statuses.

# Steps
1. Data Preparation

Load lending_data.csv into a Pandas DataFrame.
Create feature (X) and label (y) datasets.
Split data into training and testing sets.
2. Model Training & Prediction

Train a logistic regression model on the training set.
Predict loan risk using the test set.
3. Model Evaluation

Compute a confusion matrix and classification report.
Analyze accuracy, precision, and recall for each label.
# Results
Accuracy: High overall model performance.
Healthy Loans (0): Excellent precision and recall.
High-Risk Loans (1): Slight room for improvement in classification.
# Conclusion
The model demonstrates strong predictive capabilities, making it a viable tool for credit risk assessment. While it accurately identifies healthy loans, some misclassification of high-risk loans exists. Further optimization could improve performance.

# Requirements
Python Libraries: pandas, sklearn, numpy, matplotlib
Data Source: lending_data.csv