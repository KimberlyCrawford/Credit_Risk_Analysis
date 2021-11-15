# Credit_Risk_Analysis

## Overview
A Credit Risk Analysis using Machine Learning

### Purpose

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques need to be employed to train and evaluate models with unbalanced classes. Imbalanced-learn and scikit-learn libraries were used to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the data was oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm was used. Two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, was compared to predict credit risk. The performance of these models were evaluated resulting in a written recommendation on whether the models should be used to predict credit risk.

### Dependencies

Imbalanced-learn package with the following dependencies:

- NumPy, version 1.11 or later
- SciPy, version 0.17 or later
- Scikit-learn, version 0.21 or later

### Data

[Loan Stats Data](https://github.com/KimberlyCrawford/Credit_Risk_Analysis/blob/main/LoanStats_2019Q1.csv)

## Deliverable 1 Use Resampling Models to Predict Credit Risk

Using the imbalanced-learn and scikit-learn libraries, the following three machine learning models were evaluated by using resampling to determine which is better at predicting credit risk. 

1) Oversampling RandomOverSampler Algorithm



2) Oversampling SMOTE Algorithm



3) Undersampling ClusterCentroids Algorithm









## Deliverable 2 Use the SMOTEENN Algorithm to Predict Credit Risk

Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.



## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

Using your knowledge of the imblearn.ensemble library, you’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.



## Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)



### Results: 

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.



### Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

notes; By using the latest machine learning techniques, these FinTech firms can continuously analyze large amounts of data and predict trends to optimize lending.

use Python to build and evaluate several machine learning models to predict credit risk. Being able to predict credit risk with machine learning algorithms can help banks and financial institutions predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud.