# Credit-Risk-Classification
## Background

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer 
lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis

The objective of this analysis is to develop a machine learning to predict loan risk based on provided financial data. The provided dataset contains 
financial attributes for loan applicants, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks,
and total debt. Using this information, goal for the model is to predict and classify the loans into two categories: `healthy loans (label 0)` and `risky loans (label 1)`.

The analysis begins by reading the csv file `lending_data.csv`, dividing it into features with the target variable `loan_status`. The data is further split into training
and testing sets for model training and evalutaion. A Logistic Regression Model is then created from the original data. From this model, a predictions were made on the test
data. Lastly, evaluated the model's performance by generating a confusion matrix and showing the classification report.

## Results

The precision, recall, and f1 scores are as follows:

* Precision for healthy loans: 1.00
* Recall for healthy loans: 0.99
* F1 for healthy loans: 1.00
* Precision for risky loans: 0.85
* Recall for risky loans: 0.91
* F1 for risky loans: 0.88
* Accuracy score: 0.99

## Summary

The logistic regression model demonstrates outstanding capability in identifying healthy loans, achieving high precision and recall. While it exhibits slightly lower precision 
for high-risk loans, its recall remains good. The balanced accuracy score suggests a solid capability to predict both categories effectively.