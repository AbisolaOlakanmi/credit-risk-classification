# Module 12 Report Template

## Overview of the Analysis
This dataset is a historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
The data has about 77536 rows and 8 columns, the rows, reflecting how much people borrowed(loan_size), the interest rate of the loan(interest_rate), income of the borrower(borrower_income), number of accounts been held by these borrowers, derogatory_marks, total_debt, and their loan status (loan_status). Thus, value of 0 in the “loan_status” column means that the loan is healthy. And value of 1 means that the loan has a high risk of defaulting
The value_counts function reveals, approximately 3.23% (2,500) are non-performing loans, out of the 77,356 loans from the raw data




## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
 In Model 1, the accuracy score of approximately 99.18% reveals its reliability in reasonably predicting the credit worthiness of potential borrowers. The model also predicted a total of 563 defaults('1') in contrast with the actual of 619 (563 + 56), approximately 91% accurate prediction of '1' (non-performing loans or defaults), with a 0.85 precision score.



* Machine Learning Model 2:
  Model 2 accuracy score went up to approximately 99.38% from the previous 99.18%. Also, the model's predictive power of default loans rose to 99% from 91% with a slightly low precision score of 0.84, but relatively remained at approximately 99% predictive power for the healthy (performing) loan, with a precision score of 1.
