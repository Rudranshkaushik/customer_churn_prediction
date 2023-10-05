# Customer Churn Prediction

This repository contains code for predicting customer churn using machine learning. The dataset used for this project is a customer churn dataset loaded from Google Drive.

## Dataset Information

The dataset is loaded from a provided Excel file named "customer_churn_large_dataset.xlsx." It contains information about customers, including their demographics, location, subscription details, and churn status.

### Data Exploration

- The dataset's basic statistics and information are explored.
- Null values in the dataset are visualized using a heatmap.
- Histograms are created to visualize data distributions.

## Data Preprocessing

- The "CustomerID" and "Name" columns are dropped from the dataset.
- Gender and Location columns are encoded using Label Encoding for modeling.

## Exploratory Data Analysis

### Location Analysis

- Percentage of customers who churned from different locations (e.g., Los Angeles, New York, Miami, Chicago, Houston) is analyzed.

### Gender Analysis

- Percentage of males and females who churned is analyzed.

## Modeling

Three machine learning models are trained and evaluated:

1. Decision Tree Classifier
2. Random Forest Classifier
3. Support Vector Machine (SVM)

The accuracy scores of these models are displayed.

## Deep Learning Model

A deep learning model with multiple layers is created using TensorFlow and Keras. Custom metrics for accuracy, precision, recall, and F1-score are defined. The model is trained and evaluated on the dataset.

## Model Deployment

The trained deep learning model is saved to a file named "model_saved" using Pickle.

## Prediction

You can make predictions using the saved model by providing input features such as Age, Gender, Location, Subscription Length (Months), Monthly Bill, and Total Usage (GB).

The model will predict whether a customer is likely to churn (1) or not (0).
