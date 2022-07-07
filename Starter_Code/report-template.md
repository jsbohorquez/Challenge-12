# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to use machine learning in order to predict the number of healthy loans versus high risk loans.
* The financial data used for this analysis includes a variety of loan data such as loan size, interest rates, borrower income, debt to income ratio, number of customer accounts, derogatory marks, total debt and loan status. The focus on this analysis is to predict the values under loan status to identify healthy loans vs high risk loans.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    * displayed an ACCURACY level of 99%
    * displayed a PRECISION level of 100% for healthy loans ('0')
    * displayed a PRECISION level of 85% for high-risk loans ('1')
    * displayed a RECALL SCORE of 0.99 for healthy loans ('0')
    * displayed a RECALL SCORE of 0.91 for high-risk loans ('1')



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    * displayed an ACCURACY level of 99%
    * displayed a PRECISION level of 100% for healthy loans ('0')
    * displayed a PRECISION level of 84% for high-risk loans ('1')
    * displayed a RECALL SCORE of 0.99 for healthy loans ('0')
    * displayed a RECALL SCORE of 0.99 for high-risk loans ('1')
    
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Both models performed similarly, however, the second ML model would be considered more trustworthy as the oversampling of the smaller category data (1=high-risk loan) gives the model a more evenly weighted data source for higher accuracy predictions.
* Does performance depend on the problem we are trying to solve? In this case, it is more important to predict the '1' values as those would show possible high-risk loans that would negatively impact the business and reduce accuracy of correctly showing business performance.


