# Module 12 Report

## Overview of the Analysis

- The purpose of the analysis is to predict the status of a loan based on various financial factors including `loan_size`, `interest_rate`, `borrower_income`, `debt_to_income`, `num_of_accounts`, `derogatory_marks` and `total_debt`. The dataset includes 77,536 historical loans.
- The machine learning process started with splitting data into labels and variables. The next step was to split both the labels and variables into different training and testing sets. After that, we fitted a logistic regression model by using the training data and made the predictions using the testing data. Finally, we calculated the scores of the predictive model on this testing data.

## Results

The accuracy of the model is 99%. The macro-averaged and weighted-averaged precision and recall scores of the model are very high at 94% and 99% respectively.

## Summary

In summary, the logistic regression model performed very well on this dataset because of its high accuracy.
