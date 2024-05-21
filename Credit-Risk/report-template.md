# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis is to develop and evaluate machine learning models to assess the creditworthiness of borrowers. I aim to leverage historical lending data from a lending services company to build predictive models that can identify loans at a high risk of default. 

The dataset used in this analysis contains historical lending activity data, including information about borrowers and loan outcomes. Specifically, I focus on the "loan_status" column, where a value of 0 indicates a healthy loan, and a value of 1 indicates a high risk of default.

In our analysis, I was interested in predicting the credit risk of loans. The key variables include:

    Features (x): Various attributes from the dataset, such as borrower information, loan details, and financial indicators.
    Labels (y): The "loan_status" column, where 0 represents healthy loans, and 1 represents high-risk loans.

The analysis involved the following stages:

    1. Data Preprocessing
    2. Model Building
    3. Model Evaluation
    4. Reporting
    
I employed logistic regression to model the credit risk.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Accuracy was high, with a score of 94.4%.
    * Precision and recall was 0.87 for high risk loans which means the model predicts a loan as high-risk, and 0.89 for recall, which means it correctly indetifies          89% of all high-risk loans.
    * The confusion matrix reveals that the model correctly predicted most of the healthy loans but had more false negatives.

* Machine Learning Model 2:
  * Accuracy was high, with a score of 99.6%
  * Precision and recall was improved. The precision for high-risk loans remained at 0.87, indicating a consistent ability to correctly classify high-risk loans.          However, the recall for high-risk loans increased to 1.00, indicating that the model now correctly identifies all high-risk loans in the dataset.
  * The confusion matrix reveals that it correctly predicted almost all healthy loans. 


## Summary

The model that performs the best and should be used is #2 because it has better accuracy, recall, and overall predictive capability. 
