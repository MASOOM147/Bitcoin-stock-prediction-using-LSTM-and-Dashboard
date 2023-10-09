# Bitcoin-stock-prediction-using-LSTM-and-Dashboard
# Bitcoin Stock Price Prediction

## Overview
This project focuses on predicting Bitcoin stock prices using a Long Short-Term Memory (LSTM) model. We perform various tasks, including data loading, exploratory data analysis, model building, evaluation, and future price prediction.

## Loading Dataset
We start by loading the Bitcoin stock price dataset, which can be downloaded from Yahoo Finance. The dataset is stored in a CSV file and is read into a Pandas DataFrame for further analysis.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) is a crucial step in understanding the dataset. In this phase, we perform the following tasks:
- Analyze stock prices over different time periods.
- Visualize trends and patterns in the data.
- Check for missing values and outliers.
- Calculate basic statistics to gain insights into the data's distribution.

## Building LSTM Model
The heart of this project is the LSTM model used for predicting Bitcoin stock prices. This phase involves several steps:
- Data preprocessing, including normalization and feature engineering.
- Splitting the dataset into training and testing sets.
- Defining the architecture of the LSTM model, including the number of layers and neurons.
- Compiling and training the model on the training dataset.

## Model Evaluation
To assess the performance of the LSTM model, we utilize various evaluation metrics, including:
- Root Mean Squared Error (RMSE)
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Explained Variance Score
- R-squared (R2) Score
- Regression Loss

These metrics provide a comprehensive view of how well the model is performing in predicting Bitcoin stock prices.

## Predicting Next 30 Days
After successfully training the LSTM model, we leverage it to predict Bitcoin stock prices for the next 30 days. This allows us to make short-term predictions based on historical data.

## Plots and Visualizations
Visualizations play a crucial role in understanding and presenting the results of our analysis and predictions. We create various plots, including:
- Line plots to compare original and predicted stock prices.
- Time series plots to visualize trends and patterns over time.
- Error distribution plots to assess the model's accuracy.
- helu
