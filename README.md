# Credit_Risk_Classification
Supervisored_Learning_Machine
## Overview of the Analysis

The purpose of this analysis was to build and evaluate the performance of a logistic regression model used to predict the eligibility of borrowers based on historical lending data. The goal of this model was to identify whether a loan is a healthy loan or high-risk loan to aid in financial decision making.

The dataset includes financial information such as borrower's loan size, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. 

The target variable was `loan_status`, where each loan is labeled as `0` for healthy loan and `1` for high-risk loan.

## Machine Learning process

The machine learning followed these steps:
1. Data preprocessing:
    Load, examine, and clean the dataset.
    Identify and review the target variable and features.

2. Data splitting:
    Split the data into training and testing sets using `train_test_split` function with an 75 - 25 percentages.

3. Model training:
    Choose Logistic Regression model for this analysis.
    Trained a logistic regression model on the training data.

4. Model evaluation:
    Evaluated the performance of the model using a confusion matrix and classification report based on testing and prediction data.

## Results

Machine Learning Model: Logistic Regression
    Accuracy: 99%

    Precision:  Healthy loan: 100%
                High-risk loan: 87%
    
    Recall:     Healthy loan: 100%
                High-risk loan: 89%

    F1-Score:   Healthy loan: 100%
                High-risk loan: 88%

## Summary
The logistic regression model performed overall well in predicting both the healthy loan and high-risk loan with an accuaracy of 99%. The model performs best for predicting healthy loan with 100% for precision, recall and f1-score. It is slightly lower accuracy for the high-risk loan prediction with 87%, 89% and 88% respectively. 
The room for error in this logistic regression model is exceptional small, which is only 0.76% (for Flase Postive and False Negative).

Recommendation: Given the results, the logistic model is strongly recommended for classification task, in paricularly predicting loan statuses in this analysis due to its high accuracy and reliability in identifying both healthy and high-risk loans.
