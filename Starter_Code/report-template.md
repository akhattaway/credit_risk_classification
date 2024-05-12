# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    The purpose this analysis was to predict high risk and healthy loans based on borrower characteristics.

* Explain what financial information the data was on, and what you needed to predict.
    We used borrower data and load data to predict how well we might be able to predict if a borrower would default on their loan or not.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    loan status
* Describe the stages of the machine learning process you went through as part of this analysis.
    The stages of this involved splitting into traing and test sets, fitting and then putting into a logistic regression model. We then evaluated the models performance with precision, f1, recall, and accuracy metrics.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    Logistic Regression
    Confusion Matrix
    Classification

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
        Healthy Loan:
            precision = 1.00
            recall  = .99
            f1-score = 1.00   
        
        High Risk Loan:
            precision = .84
            recall  = .94
            f1-score = .89

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
    THe logistic regression model seems to perform well, it seems to be able to predict healthy loans at a higher rate thatn High Risk. 

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
        Yes, performace does depend on the problem we are trying to solve. For example credit risk might allow for more tolerance that medical devices.

If you do not recommend any of the models, please justify your reasoning.
    In this scenario, the ability to predict the loans that will be paid back is strong and the ability to predict those that will default also works well and I would recommend the logistic model.
