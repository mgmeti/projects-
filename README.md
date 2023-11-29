# projects-
# Prediction of Santander Customer Satisfaction
## Introduction

Every organization needs happy customers and unhappy customers.

The main motivation is the challenge of working with hundreds of anonymized features to predict if a customer is satisfied or dissatisfied with their banking experience.

The task is to predict the probability of unsatisfied customers in the test set.

We have implemented logistic regression, a decision tree classifier, and some ensemble models of the decision tree classifier compared the results, and chose the best model from the lot.


##  Data Overview
Train Data:  76020 rows, 371 columns

Test Data: 75818 rows, 370 columns. (TARGET is excluded from Test data.)

Imbalanced data: minority class < 4%

All predictors are numerical.

Target: categorical.

Group of features starting with imp_, num_, saldo_, deltaimp, deltanum, ind_.

Other features: var3, var15, and var38.


## Pre-Processing

No null values.
Constant features removed = 34 (Variance threshold=0)
Quasi: constant features removed = 99 (Variance threshold = 0.01)
Duplicate features removed: 17
Correlated feature removal = 51 (Correlation threshold = 0.98)
Overall, 369 features were reduced to 204 features.
Standardize the features using StandardScaler().








