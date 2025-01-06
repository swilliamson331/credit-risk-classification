# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge:

The purpose of this analysis was to create a machine learning model that predicts if a loan would be healthy, or be at high risk of defaulting. I trained this model using data such as:loan size, interest rate, borrower income, debt to income ratio, total debt, number of accounts, and derogatory marks.

To create this model, I assigned the loan status to the y and the rest of the features to x, and split the overall dataset into a training and testing datasets using "train_test_split". I then fit a logistic regression model on the training data, and had that model make predictions on the testing data. A classification report gave the accuracy results of the model.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

- Accuracy Score: Accuracy score is the total correct predictions divided by total predictions. Is the overall accuracy of the entirety of the model. 
- Precision Score: Precision score is true positive predictions divided by all positive predictions. Essentially, how accurate positive predicitions are by the model.
- Recall Score: Recall score is true positive predictions divided by all positives in the dataset. Essentially, how good is the model at identifying positive instances.

## Summary

Summarize the results of the machine learning model:

The model predicts the healthy loans very accurately. The model predicts high-risk loans pretty well also, but has more false positives than false negatives as shown by its lower precision score. Overall , even though the model is prone to some false positive results on high risk loans, the model has accurate predicitions overall. And in the conext of identifying high risk loans, it is better to have more false positives and be safe rather than sorry. This makes the recall score of .94 more important, as false negatives (high risk loans deemed healthy) would be more detrimental. The model is pretty accurate, but if the company can't withstand high risk loans going undetected 6% of the time, it would be understandable to not use the model.
