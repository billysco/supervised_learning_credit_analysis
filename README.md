# supervised_learning_credit_analysis
Using logistic regression to identify credit risks of various borrowers
## Overview of the Analysis

This analysis was conducted to evaluate levels of credit risk while accounting for the imbalance of healthy vs risky loans. Utilizing a dataset of historical lending activity, the program aims to predict which loans were safe and which loans were at a high default risk. Risky loans are represented with a 1 and healthy loans are represented with a 0. The first process used was LogisticRegression. Then RandomOverSampler is applied to resample the data due to the imbalance of healthy and risky loans. Finally, another LogisticRegression is applied to the new data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models.

* LogisticRegression:
  * The Accuracy is 99%, Precision is 99%, and Recall is 99%.

* LogisticRegression with RandomOverSampler:
  * The Accuracy is 99%, Precision is 99%, and Recall is 99%.

## Summary

Although both models perform very well, the model with RandomOverSampler is recommended. The accuracy metrics for both models are very similar, but the random sampler only classified 4 risky loans as safe whereas the model without RandomOverSampler classified 56 risky loans as safe. 