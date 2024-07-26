# credit-risk-classification2
Supervised Learning - Module 20 Challenge


## Overview of the Analysis

This code uses the dataset from _Credit_Risk\Resources\lending_data.csv_ to create a logistic regression model to help predict credit risk for loans.  Healthy loans are labeled 0 and high-risk loans are labeled 1.
The dataset includes historical information from 77,536 loans.  The information includes loan_size, interest_rate, borrower_income, debt_to_income ratio, number_of_accounts, derogatory_marks, total_debt, and loan_status.  The loan_status indicated if the loan was healthy (0) or high-risk (1).  While the other features such as oan_size, interest_rate, borrower_income, debt_to_income ratio, number_of_accounts, derogatory_marks, and total_debt helped in predicting the loan_status.  75% of the dataset was used in training the model and 25% was use in the testing of the model.

## Results

The Classification Report for logistic regression model shows
* Accuracy Score: 0.99
* Precision Score (High-Risk Loans): 0.85
* Recall Score (High-Risk Loans): 0.91
* Precision Score (Healthy Loans): 1.00
* Recall Score (Healthy Loans): 0.99
   

## Summary

The logistic regression model preforms well in predicting if a loan is healthy or at high-risk.  As seen from the Classification Report, the precision = 1.00 and the recall = 0.99 indicates that the model correctly identifies the healthy loans (class = 0).  While the precision = 0.85 and the recall = 0.91 for the high-risk loans (class = 1).  This means that there are more false positives than false negatives, but still does a good job at prdicting if a loan is high-risk or healthy.
