# Vaccine-Receiver-Prediction-Model


## Problem Statement
The goal here is to predict how likely individuals are to receive their xyz and seasonal flu
vaccines. Specifically, predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine.

## Solution
In this multi label classification problem, I have made predictions using 3 models.
1. Logistic regression model
2. Random forest model
3. XGBoost classifier model

Each model gave ROC AUC score in range 0.84 ± 0.03

The test prediction(submission_format.csv) mentioned in this repository is of random forest model which gave maximum ROC AUC score.
