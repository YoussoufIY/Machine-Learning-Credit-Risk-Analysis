# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to provide the bank with the ability to determine whether or not a customer requesting a loan 
can be determined to be at risk of a default before making the loan. 

By using a machine learning model to predict a customer's credit worthiness, we can improve risk mitigation and minimize potential losses. 

## Accuracy scores

### Healthy Loans

*Precision: 100%. Precision refers to the percentage of correct positive predictions, measuring how many false positive predictions were made by the model. Meaning that 100% of predicted healthy loans were actually healthy.
*Recall: 99%. Recall refers to the percentage of actual positive cases the model predicted, measuring how many false negative predictions were made by the model. Meaning that 99% of predicted healthy loans were actually healthy. 
*F1 Score: 100%. F1 is the mean of precision and recall. It'S a single emaure of the model's accuracy in predicting healthy loans. The model reached a perfect balance between precision and recall. 


### High-Risk Loans

*Precision: 84%. For high-risk loans, the model produced a higher number of false positives, meaning that 16% of predicted high-risk loans were actually healthy.
*Recall: 99%. For high-risk loans, the model performed well on recall. Meaning that it produced very few false negatives. 
*F1 Score: 91%. The overall accuracy of the model at 91% for high-risk loans.

## Summary

I recommend this model be used for predicting future customer's creditworthiness. It's lack of perfect accuracy with regards to high-risk loans can be mitigated by adding a layer of review by human credit analysts. This way, the small percentage of customers that would be denied by the model but were actually not at risk of default, will also get a chance to get their loans approved. 

This will minimize labor costs for banks by reducing the number of credit analysts needed to review loan applications, while mitigating the risk of lost revenue from poor predictions by the model.
