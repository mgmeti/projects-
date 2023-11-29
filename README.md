# projects-
# Prediction of Santander Customer Satisfaction
## Introduction

Every organization needs HAPPY customers and no unhappy customers.

The main motivation is the challenge of working with hundreds of anonymized features to predict if a customer is satisfied or dissatisfied with their banking experience.

The task is to predict the probability of each customer in the test set being unsatisfied.

We have implemented logistic regression, decision tree classifier and some ensemble models of decision tree classifier and compared the results and chose the best model from the lot.


##  Data Overview
Train Data:  76020 rows, 371 columns

Test Data:  75818 rows, 370 columns. (TARGET is excluded from Test data.)

Imbalanced data – minority class < 4%

All predictors - Numerical. 

TARGET – categorical.

Group of features starting with imp_, num_, saldo_, deltaimp, deltanum, ind_.

Other features – var3, var15, var38.
