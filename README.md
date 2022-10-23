# Credit_Risk_Analysis
Module 17 Challenge

## Overview of Analysis
The purpose of this analysis is to review the level of accuracy, precision, and recall scores of six different machine learning models. 

## Results
There were 2 groups of models leverage Resammpling models and Ensemble Models. Each method has it's Accuracy along with it precision and recall scores in generated in the Machine Learning Environment as example below for Random Oversampling
#### Figure 1: Examples of Python Output
![](https://github.com/NortonAAA/Credit_Risk_Analysis/blob/main/images/accuracy_score_example.png)
![](https://github.com/NortonAAA/Credit_Risk_Analysis/blob/main/images/imbalanced_summary_example.png)
#### Resampling Models
1. Naive Random Oversampling
2. Synthetic Minority Oversampling Technique (SMOTE)
3. Cluster Centroid Undersampling
4. Combination (Over/Under Sampling) - Synthetic Minority Oversampling Technique with Edited Nearest Neighbor (SMOTE-ENN or SMOTEENN)

#### Ensemble Models
1. Balanced Random Forest Classifier
2. Easy Ensemble AdaBoost Classifier

#### Figure 2: Summary of All Models
![](https://github.com/NortonAAA/Credit_Risk_Analysis/blob/main/images/all_model_summary.png)

## Summary
As above, we can see that the Easy Ensemble AdaBoost has the highest level of accuracy without overfitting the data. Interestingly all models have a average precision of 0.99 (practically 1) while the Easy Ensemble AdaBoost had a 0.07 precision on high risk loans. We would also select the Easy Ensemble AdaBoost for the higher level of completeness in recall scores on both high risk and low risk loans.