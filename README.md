# Diabetes Prediction Machine Learning Model

## Overview

This project implements a machine learning model to predict diabetes based on the PIMA Diabetes dataset. The model utilizes a Support Vector Machine (SVM) classifier with a linear kernel.


## Project Explanation

Data Collection and Analysis:

The PIMA Diabetes dataset is loaded into a pandas DataFrame.
Some basic data analysis is performed, such as checking the shape, describing the statistical measures, and examining the distribution of the target variable ('Outcome').
The features and labels are separated into X and Y, respectively.
Data Standardization:

Standardization is performed on the feature data using StandardScaler from scikit-learn.
Train-Test Split:

The dataset is split into training and testing sets using the train_test_split function.
Training the Model:

A Support Vector Machine (SVM) classifier with a linear kernel is instantiated and trained on the training data.
Model Evaluation:

The accuracy score is calculated for both the training and testing datasets.
Making Predictions:

A sample input data point is provided, standardized, and used to make a prediction with the trained SVM classifier.
The prediction result is then printed.

## Dependencies

- numpy
- pandas
- scikit-learn

Install dependencies using:

```bash
pip install numpy pandas scikit-learn


