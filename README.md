# Module 12 Report Template

## Overview of the Analysis

In this analysis, our goal was to develop machine learning models for credit risk assessment. We aimed to predict the likelihood of loans defaulting or being high-risk based on various financial indicators. The dataset provided contained information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The task was to predict the loan status, where 0 represents healthy loans and 1 represents high-risk loans.

We followed a standard machine learning process, which involved data preprocessing, model training, and evaluation. After exploring the dataset and understanding its structure, we split the data into training and testing sets. Then, we applied logistic regression, a commonly used algorithm for binary classification tasks like credit risk assessment.

## Results

* **Machine Learning Model 1: Logistic Regression**
    - **Accuracy:** The model achieved an accuracy score of 99%, indicating that it correctly classified 99% of the loan cases.
    - **Precision:** For healthy loans (label 0), the precision score was 100%, implying that all loans predicted as healthy were indeed healthy. For high-risk loans (label 1), the precision score was approximately 86%, indicating that about 86% of the loans predicted as high-risk were truly high-risk.
    - **Recall:** The recall score for healthy loans was 100%, suggesting that the model correctly identified all healthy loans. For high-risk loans, the recall score was about 91%, indicating that approximately 91% of actual high-risk loans were correctly identified by the model.

## Summary

The logistic regression model performed exceptionally well in predicting credit risk, with high accuracy, precision, and recall scores. It effectively differentiated between healthy and high-risk loans, making it a valuable tool for credit risk assessment. Therefore, we recommend deploying this model for use by the company.

This model can help the company make informed lending decisions, optimize risk management strategies, and minimize potential losses due to defaults. Continuous monitoring and updates of the model are essential to ensure its effectiveness in adapting to evolving market conditions and regulatory requirements.

Overall, the logistic regression model offers significant benefits to the company in managing credit risk and maintaining a healthy loan portfolio.
