# CSC2515Project - Predicting Fama-French Factors Using Machine Learning Techniques

In this repository you will find the code behind our paper "Predicting Fama-French Factors Using Machine Learning Techniques" which is the PDF in the repository.

A quick breakdown of how this repository is organized.

Modelling ('AdaBoosting.py', 'Gradient Boosting.py', 'GRU.ipynb', 'Logistic Regression.ipynb', 'SVM_RF_MLP.ipynb').
- These files contain the underlying code used to come up with the predictions made for the Fama-French Factors.

Data ('fama_french_data.csv')
- This CSV contains all of the data (features and targets) used in training/validation/testing.

Results (Folder:'Results')
- This folder contains 'Predicts_all.xlsx', an Excel file containing all of the models' predictions.
- This folder also contains 'monthly_returns.csv' which breaks down the performance of all passive/active strategies based on these models.
- The folder 'Feature Importance' contains the feature importances for the outputted random forest and logistic regression models.

Other ('CumulativeReturns.ipynb', 'FeatureImportances.ipynb')
- These are scripts which calculated cumulative returns and random forest feature importances.
