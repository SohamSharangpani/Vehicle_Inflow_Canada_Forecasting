# Vehicle Inflow Canada Forecasting
BIA5402_Group_Project

## Overview

This project implements and evaluates various time series forecasting models to predict the total number of vehicle entries. The analysis includes classical statistical models like ARIMA and Exponential Smoothing, as well as more advanced machine learning models such as Prophet and Long Short-Term Memory (LSTM) networks. The project analyzes the entire available dataset and also focuses on the last three years of data to assess recent predictive performance.

The core analysis is performed within the `forecasting_analysis.ipynb` Jupyter Notebook located in the `notebooks/` directory. This notebook contains the following steps:

1.  **Data Loading and Exploration:** Loading the time series data and performing initial exploration.
2.  **Data Preprocessing:** Handling missing values (if any) and preparing the data for modelling. This includes splitting the data into training and testing sets for both the entire dataset and the last three years.
3.  **Model Implementation and Evaluation:**
    * **ARIMA:** Implementation of ARIMA models with different order parameters.
    * **Exponential Smoothing:** Implementation of Simple Exponential Smoothing, Holt's Linear Trend, and Holt-Winters methods (Additive and Multiplicative).
    * **Prophet:** Implementation of the Prophet forecasting model.
    * **LSTM:** Implementation of a Recurrent Neural Network with LSTM layers.
4.  **Prediction Storage:** Storing the predictions from each model for both the entire dataset and the last three years.
5.  **Performance Metric Calculation:** Calculating RMSE, MAE, MAPE, and MSE for each model's predictions on the test sets.
6.  **Results Comparison:** Presenting the performance metrics in a table for easy comparison across models.
7.  **Visualization:** Plotting the actual values against the predictions of selected models (e.g., Simple Exponential Smoothing, LSTM) for the last three years.
8.  **Conclusion:** Summarizes the findings and discusses the performance of the different forecasting models.

