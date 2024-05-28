# Credit-Risk-Analysis
________________________________________________________________
## Overview

Loan applicants are assessed for lending risk using a logistical regression supervised learning model. The main financial information this analysis utilized were loan size, income, total debt, interest rate, debt-to-income ratio, number of accounts, and derogatory marks. These were stored in the x-values. Applicant data was categorized so that the y-label encompassed an applicant's status: "0" indicated healthy, while "1" indicated that they were risky. Once the x and y values were operationalized, a training set of data was derived from the dataset for the supervised learning model to train on. A logistical regression analysis was used to determine the relationship between the x-values to the y-values. Accuracy, precision, and recall scores were assessed through the confusion matrix.

## Machine Learning Model Results
* Healthy Loan Label: 100% precision, 99% recall, an f-score of 1.00 indicating 100% prediction accuracy. 
* High-risk Loan Label: 85% precision, 91% recall, an f-score of 0.88 indicating 88% prediction accuracy. 

## Summary

Overall high ratings of accuracy across the labels indicates the models reliability in making predictions for either healthy or risky lending. Yet, the model's ability to predict healthy loans outperforms that of its ability to predict high-risk loans. The recall scores characterize the percentage of instances that were correctly identified across the actual number of instances that were encompassed in the dataset. 

The performance of models is useful for evaluating how effectively we can represent the dataset, but it's not the only reason for choosing a specific model. Assessing the relevance of the problem we're addressing and how well the proposed models align with it is also crucial when considering their suitability for analyzing the data. In this case, there is the question of whether it's more important to predict the `1`'s, or predict the `0`'s. The answer to this depends on the lender's goals and risk tolerance - is the glass half-full or half empty? The Healthy Loan label offers few false positives or missed healthy loans. Adopting the metrics associated with the High-risk Loan label may mitigate potential losses or adhere more closely to regulatory requirements. 