# credit-risk-classification
Module 20 Challenge Due 08/22/2024
## Purpose
- The purpose of this analysis is to determine if an applicant is a “healthy loan” or a “high risk loan” based on a variety of factors including the applicant’s loan size, interest rate, income, and debt. We will be training a model on this information and using it to categorize applicants.
## Logistic Regression Results
- Accuracy: 0.92
- Healthy Loans
     - Precision: 1.00
     - Recall: 0.99
- High Risk Loans
     - Precision: 0.92
     - Recall: 0.91
## Summary
The logistic regression model is adept at predicting both “healthy loans” and “high-risk loans” as all outputs for accuracy, precision, and recall are above 0.85. Though it is slightly worse at predicting high-risk loans with a precisions and recall score of 0.92 and 0.91 compared to 1.00 and 0.91. This could potentially mean that the model is less able to identify high-risk loans.
I would recommend use of the model because the values of observational error are within an acceptable range
