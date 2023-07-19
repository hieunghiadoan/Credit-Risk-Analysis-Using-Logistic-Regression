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
## Summary

Based on the results, the logistic regression model trained with original data, particularly in predicting high-risk loans. This model demonstrates higher precision and recall scores for high-risk loans, which is crucial in minimizing potential financial losses for the lending company.

I recommend using the logistic regression model trained with original data for credit risk analysis, as it shows a significant improvement in predicting high-risk loans compared to the original model. This model will help the company effectively assess loan applications and make informed decisions when approving or rejecting loans, thus mitigating credit risk.
