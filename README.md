# Credit-Card-Default-Classification

2nd Assignment Programming for Big Data

Abstract

This Jupyter Notebook is a showcase of various machine learning modelling methods, as well as data treatment methods and model evaluation.
Dataset

The data have been downloaded from https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients. The data show information about default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

The aim is to predict which customer more likely will default.

There is one binary variable, default payment (Yes = 1, No = 0), as the response variable.

There are 23 variables as explanatory variables:

    LIMIT_BAL (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.

    Sex (1 = male; 2 = female).

    Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

    Marital status (1 = married; 2 = single; 3 = others).

    Age (year).

PAY_0 - PAY_6: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows:

    PAY_0 = the repayment status in September, 2005;
    PAY1 = the repayment status in August, 2005; . . .;
    PAY_6 = the repayment status in April, 2005.

The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

BILL_AMT1 - BILL_AMT6: Amount of bill statement (NT dollar).

    BILL_AMT1 = amount of bill statement in September, 2005;
    BILL_AMT2 = amount of bill statement in August, 2005; . . .;
    BILL_AMT6 = amount of bill statement in April, 2005.

PAY_AMT1 - PAY_AMT6: Amount of previous payment (NT dollar).

    PAY_AMT1 = amount paid in September, 2005;
    PAY_AMT2 = amount paid in August, 2005;...;
    PAY_AMT6= amount paid in April, 2005.
