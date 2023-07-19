# Credit Risk Analysis

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of two logistic regression machine learning models in predicting the credit risk associated with loans. The analysis was conducted on financial data, specifically focusing on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, either as a healthy loan (0) or high-risk loan (1).

The stages of the machine learning process in this analysis included:

1. Splitting the data into training and testing datasets
2. Creating and fitting a logistic regression model with the original data
3. Evaluating the model's performance using accuracy, precision, and recall scores

Methods used in this analysis include LogisticRegression 

## Results

## Machine Learning Model : Logistic Regression with Original Data

### Description of Model: Accuracy, Precision, and Recall scores.

Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances.
Precision:
 - Healthy loans (0): The model has a precision of 1.00, which means it's excellent at identifying true positives with very few false positives.
 - High-risk loans (1): The model has a precision of 0.87, indicating its moderate effectiveness in identifying high-risk loans with some false positives.
Recall:
 - Healthy loans (0): The model has a recall of 1.00, which means it's correctly identifying nearly all instances of healthy loans with very few false     negatives.
 - High-risk loans (1): The model has a recall of 0.89, indicating its effectiveness in identifying high-risk loans with some false negatives.
