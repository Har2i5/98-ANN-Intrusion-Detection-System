# Network Intrusion Detection System (NIDS)

## Overview
This repository contains a notebook that implements a Network Intrusion Detection System (NIDS) using Logistic Regression and Artificial Neural Networks (ANN). The goal is to predict whether network traffic is classified as Normal or Anomaly.

## Dataset
The dataset used for this analysis includes features related to network traffic, which allows for the identification of potential intrusions. The data is divided into training and testing sets.

## Key Steps
Data Loading: The dataset is loaded from CSV files, enabling subsequent analysis.
Exploratory Data Analysis (EDA): An EDA was conducted to understand the distribution of the data and identify any patterns or anomalies.
## Model Development:

Logistic Regression: A baseline model was built using logistic regression.

Artificial Neural Networks (ANN): An ANN model was developed, which outperformed the logistic regression model.

## Prediction

The ANN model predicts probabilities for each instance in the test set.

A threshold of 0.8 was applied to convert predicted probabilities into binary classifications:

Anomaly (1): If the probability exceeds 0.8.

Normal (0): If the probability is 0.8 or lower.

## Model Evaluation

The ANN model achieved an accuracy of 98%

96% of instances predicted as normal were accurately classified.

100% of instances predicted as anomalies were correctly identified.

## Model Saving

The trained model was saved for future use.

## Requirements
To run this notebook, you will need the following Python libraries:

Pandas,NumPy,Matplotlib,Seaborn,Scikit-learn,Keras (or TensorFlow)

## Source

kaggle datasets download -d sampadab17/network-intrusion-detection
