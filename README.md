# Predicting-the-Criminals
There has been a surge in crimes committed in recent years, making crime a top cause of concern for law enforcement. If we are able to estimate whether someone is going to commit a crime in the future, we can take precautions and be prepared. You are given a dataset containing answers to various questions concerning the professional and private lives of several people. A few of them have been arrested for various small and large crimes in the past. Use the given data to predict if the people in the test data will commit a crime. The train data consists of 45718 rows, while the test data consists of 11430 rows.

# The evaluation metric is Matthews correlation coefficient
        https://en.wikipedia.org/wiki/Matthews_correlation_coefficient

My repository contains all necessary files :

Python code in Jupyter : criminals.ipynb
Criminal training dataset : criminal_train.csv
Criminal test dataset : criminal_test.csv
Predictions or results : y_test_predictions.csv

# My project work uses Random Forest Classifier model with Standard Scaling to determine whether the person will commit a crime or not.

# Solution obtains 0.77914 Matthews Correlation Coefficent (Quality will increase in future by more Feature processing)
