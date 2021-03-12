# sensor-activity-classification

## Author:
Rahul Bethavalli
MSDS(Masters in Data Science), University of San Francisco

## Overview: 

Leveraging smartphone sensor readings to classify the activities being performed by the user. Compare various models and their performance for the classification of activities based on the sensor readings.

## Description:

The intertial sensor readings recorded from smartphones users can be used to classify the activity being performed by the user, given that we have a good amount of supervised labelled data for these observations. 

This project covers the end to end data science workflow. It fetches the data, does preprocessing, fits various machine learning multiclassification models and compare them, perform hyperparameter tuning and evalute the models on test data and propose a finalized best model for the classification.

HAR classification can be useful in many fileds like healthcare, fitness industry etc. The end user can be given recommendations/ suggestions based on these activities which makes the model more relevant to current day.

The evaluation shows that a Logistic Regression model performs the best and is more general than compared to other classification models and can be used to model the data and predict the target activities.
