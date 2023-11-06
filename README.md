# Welcome to Customer-Banking-Loan-Modelling-Project
***

## Task
The primary problem is predictive modeling for loan acceptance. It involves analyzing a dataset with various 
attributes to predict whether a customer will accept a personal loan.

The challenge lies in effectively preprocessing the data, selecting relevant features, 
training a machine learning model, evaluating its performance, and drawing meaningful insights from the results. 
Ensuring accuracy and avoiding overfitting are common challenges in predictive modeling. 

## Description
The problem is solved by performing the following steps:

    1. Data Loading: The dataset is loaded using Pandas to prepare it for analysis.
    2. Data Cleaning: Data cleaning is performed to handle missing values.
    3. Data Exploration: The code includes functions to visualize data through histograms 
       and scatter matrices to understand relationships between attributes.
    4. Correlation Analysis: A correlation matrix is generated to identify attributes that 
       correlate with the target variable, 'Personal Loan.'
    5. Model Training and Evaluation: 
       A). A logistic regression model is trained, and its performance is evaluated using various metrics 
           such as accuracy, precision, recall, and F1 score.
       B). A Gradient Boosting Classifier model is trained, and its performance is evaluated using various metrics 
           such as accuracy, precision, recall, and F1 score.
    6. Insights: Insights are drawn from the results, including which attributes have the most influence on loan acceptance.

## Installation
The code is written in Python, and the libraries used include 
Pandas, Matplotlib, Scikit-Learn, and potentially others.

To install the required Python packages, you can use pip:

    pip install pandas matplotlib scikit-learn

## Usage
To use the code, you would typically follow these steps:

    1. Load and preprocess your dataset.
    2. Utilize the provided functions to analyze the data, generate visualizations, and calculate correlations.
    3. Train and evaluate a logistic regression model using your dataset.
    4. Review the model's performance metrics to assess its predictive capabilities.
    5. Draw insights from the results to make informed decisions or take actions based on the analysis.

Example usage may involve loading your dataset and calling functions like train_and_evaluate_logistic_regression(data) or plot_scatter_matrix(data) to perform specific tasks within your data analysis pipeline.
