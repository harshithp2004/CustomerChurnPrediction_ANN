# Customer Churn Prediction using Artificial Neural Networks
## Overview
This project uses an Artificial Neural Network (ANN) to predict customer churn based on various customer attributes. The model was developed and tested in Google Colab, leveraging data preprocessing, exploratory data analysis, model training, evaluation, and interpretability techniques.

## Dataset
The dataset used in this project is Churn_Modelling.csv, which includes customer information such as credit score, geography, gender, age, tenure, balance, number of products, etc., to predict the likelihood of a customer leaving (churning) a bank.

## Tool/Software Used:
Google Colab

## Project Structure
Importing Libraries: Import essential libraries like pandas, NumPy, seaborn, and TensorFlow.

Loading and Inspecting the Dataset: Load the dataset and examine its structure, columns, and statistics.

Exploratory Data Analysis (EDA): Visualize data distributions and relationships to gain insights and detect patterns.

Data Preprocessing: Clean the dataset, handle categorical data, scale features, and split the data into training and test sets.

Building the ANN Model: Build and train an ANN model with Keras, with options for regularization and early stopping.

Evaluating Model Performance: Plot training and validation accuracy over epochs.

Making Predictions: Evaluate model performance on new and existing customer data.

Model Interpretability with SHAP: Use SHAP values to understand feature importance.

Confusion Matrix and Classification Report: Analyze model predictions with a confusion matrix and classification report.

## Requirements
Python 3.7+

Libraries: numpy, pandas, matplotlib, seaborn, tensorflow, scikit-learn, shap

## Usage
1. Data Analysis: Perform EDA to understand data patterns and relationships.
2. Model Training: Train the ANN model with specified parameters and visualize performance.
3. Prediction: Use the trained model to predict customer churn for new or existing data.
4. Interpretability: Analyze feature importance with SHAP values to understand model behavior.

## Results
The model achieves a training accuracy of approximately 85.5% and a test accuracy of approximately 86.2%. The confusion matrix and classification report provide additional insights into performance across different churn classes.

## Future Enhancements
Hyperparameter Tuning: Implement grid search or random search for better performance.

Advanced Models: Experiment with other algorithms like gradient boosting for comparison.

Additional Features: Incorporate additional customer insights or behavioral data if available.

