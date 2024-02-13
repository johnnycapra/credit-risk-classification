# credit-risk-classification

## Overview of the Analysis

**Purpose:** In this challenge, I used supervised machine learning with python to build a logistic regression model to determine if a borrowers credit is worthy of a loan. The model predicts if the borrower is a healthy loan or high-risk loan.

**The Data:** I used a dataset called lending_data.csv, found in the Resources folder.  The data included was the borrowers loan size, interest_rate, borrow_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt and loan_status

**Target Variable:** I targeted the loan_status to determine if the loan was healthy or high-risk then used the value_counts method to get a total for each. 

**Machine Learning Process:** 

1. Import the lending_data.csv file and create a dataframe. 
2. Preprocess data, separating the features from the labels.
3. Build model by splitting data in testing and training sets using train_test_split.
4. Train logistic regression model using the training data from above. 
5. Evaluate the models performace by calculating the accuracy score, generating a confusion matrix, and printing the classification report. 

## Results 

* Machine Learning Model 1:
    *  The accuracy for the model is .99 for predicting both healthy and high-risk loans.
    * The precision for high-risk loans is 0.84, meaning it makes less false positive predictions.
    * The recall is 0.94, collecting the majority of high-risk loans correctly. 

* Machine Learning Model 2:
    * The accuracy for the oversampled model is 0.99 for predicting both healthy and high-risk loans.
    * The precision for high-risk loans is 0.84, meaning it makes less false positive predictions.
    * The recall is 0.99, effictively collecting the majority of high-risk loans.


## Summary 

    These models seem to perform well in predicting both healthy and high-risk loans. The oversampled data predicts both the healthy loan and high-risk loans better.  There's no suprise that the predictions are similar, although, the oversampled regression has a higher recall rate for high-risk loans, making it the better option. With the recall rate being 0.99 for high-risk loans, we see that it was more effictive in correctly identifying them. My only concern is that the oversampled model is at a higher risk for overfitting. 


