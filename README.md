# Credit_Risk_Analysis

## Overview
- This analysis was done to determine how risky a loan would be based on a number of factors related to the customer. 
- Due to the natural imbalance, many more good loans exist than risky ones, a number of different techniques were used to elevauate the data.
- Resampling was done using imbalanced-learn and scikit-learn libraries. 
- RandomOverSampler and SMOTE algorithims were used to oversample, as well as CLusterCentroids algorithm for undersampling the data. 
- Two different machine learning models, BalancedRandomForest and EasyEnsembleClassifier were compared to reduce bias and predict credit risk. 

## Results
- First resampling was done to predict credit risk. 
- The data provided looked at a number of metrics including loan amount, interest rate, installment, home ownership, annual income, loan status and if a payment plan was in place. We specifically looked at loan status (low risk or high risk) data.
- We learned that 51,366 were low risk and 246 were high risk.
- Then we looked at random oversampling which brought the high risk and low risk accounts

## Summary
