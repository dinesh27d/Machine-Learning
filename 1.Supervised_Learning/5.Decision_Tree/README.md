# Decision Tree Classifier

A Decision Tree is a supervised machine learning algorithm used for both classification and regression tasks. It works by splitting the data into subsets based on feature values, recursively creating branches until it reaches a decision or outcome. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.

In this context, the Decision Tree is used to predict the likelihood of an individual earning more than 100k based on their company, job, and degree.

## Decision Tree Classifier for Salary Prediction

This project demonstrates the use of a Decision Tree Classifier to predict whether an individual earns more than 100k based on their company, job, and degree. The model is trained on a dataset containing these features and uses them to classify the salary level.

## Overview

### 1. Data Preparation

- The data is read from a CSV file containing information on various features like the company, job, and degree of individuals, along with a target column indicating whether they earn more than 100k.
- The target column, `salary_more_then_100k`, is separated from the feature columns to serve as the output we want to predict.

### 2. Label Encoding

- The features `company`, `job`, and `degree` are categorical (non-numeric) and need to be converted into numeric values for the machine learning algorithm to process them. This conversion is performed using `LabelEncoder` from `sklearn`, which assigns a unique number to each category.

### 3. Feature Transformation

- New numeric columns (`company_n`, `job_n`, `degree_n`) are created to store the encoded values of the original categorical features.
- The original categorical columns are then dropped, leaving only the numeric representations for model training.

### 4. Model Training

- A Decision Tree Classifier is instantiated and trained using the numeric features and the target column. The model learns to associate patterns in the features with the target outcome, allowing it to make predictions on new data.

### 5. Model Evaluation

- The model’s accuracy is evaluated by comparing the predicted outcomes with the actual target values. The score indicates how well the model performs on the training data.

### 6. Predictions

- The trained model is used to predict whether individuals with specific feature values (e.g., a specific company, job, and degree) earn more than 100k. The predictions are based on the decision rules learned during training.

## Conclusion

This project showcases a straightforward approach to using a Decision Tree Classifier for a binary classification problem. It involves transforming categorical data into a format suitable for machine learning, training the model, and interpreting the results of the model's predictions.

The implementation provides a clear and concise example of how machine learning models can be used to predict outcomes based on categorical features, with potential applications in various domains such as finance, human resources, and more.

