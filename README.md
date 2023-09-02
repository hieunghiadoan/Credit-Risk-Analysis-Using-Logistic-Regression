# Credit Risk Analysis Using Logistic Regression: Model Comparison and Recommendations

**Analysis Overview:**

The aim of this analysis is to assess the performance of two logistic regression machine learning models in predicting credit risk associated with loans. The analysis utilized financial data, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt, to predict loan status as either a healthy loan (0) or a high-risk loan (1).

**Stages of the Machine Learning Process:**

1. **Data Split:** The dataset was divided into training and testing datasets.
2. **Model 1 - Logistic Regression with Original Data:** A logistic regression model was created and fitted using the original data.
3. **Evaluation of Model 1:** Model 1 was assessed using accuracy, precision, and recall scores.
4. **Resampling Data:** The dataset was resampled using RandomOverSampler to address class imbalance.
5. **Model 2 - Logistic Regression with Resampled Data:** Another logistic regression model was created and fitted using the resampled data.
6. **Evaluation of Model 2:** Model 2 was evaluated using the same metrics as Model 1.

**Results:**

**Model 1 - Logistic Regression with Original Data:**
- Accuracy: 0.99
- Precision (Healthy loans - 0): 1.00
- Precision (High-risk loans - 1): 0.87
- Recall (Healthy loans - 0): 1.00
- Recall (High-risk loans - 1): 0.89

**Model 2 - Logistic Regression with Resampled Data:**
- Accuracy: 0.99
- Precision (Healthy loans - 0): 0.99
- Precision (High-risk loans - 1): 0.99
- Recall (Healthy loans - 0): 0.99
- Recall (High-risk loans - 1): 0.99

**Summary:**

The logistic regression model trained with resampled data (Model 2) outperforms the model trained with the original data (Model 1) in predicting credit risk, particularly for high-risk loans. Model 2 exhibits higher precision and recall scores for high-risk loans, which is crucial for minimizing potential financial losses for the lending company.

**Recommendation:**

I recommend using the logistic regression model trained with resampled data (Model 2) for credit risk analysis. This model demonstrates a significant improvement in predicting high-risk loans compared to the original model. Utilizing Model 2 will enable the company to effectively evaluate loan applications and make informed decisions when approving or rejecting loans, ultimately mitigating credit risk and enhancing the overall lending process.