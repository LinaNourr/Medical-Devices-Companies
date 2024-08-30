# Medical-Devices-Companies
This repository contains a project that analyzes and forecasts the quarterly revenue of various medical device companies using time series analysis methods.


## Project Overview
The goal of this project is to analyze the financial performance of medical device companies over time and use various models to forecast future revenue. This analysis can help in making informed business decisions and understanding trends in the medical device industry.

## Dataset Description
The dataset used in this project contains quarterly revenue data for several medical device companies. The data spans multiple years, providing a comprehensive view of the financial trends within the industry. Key information in the dataset includes:

Company Name: The name of the medical device company.
Quarterly Revenue: Revenue figures for each quarter, which have been converted from string to numeric format for analysis.
Date Information: Dates constructed by mapping quarters to specific months and combining them with the year.

## Data Preprocessing and Visualization
Several preprocessing steps were performed on the dataset to ensure accurate analysis:

Data Cleaning: Unnecessary columns (e.g., 'Category', 'Image') were removed, and columns were renamed for clarity.
Data Reshaping: The dataset was transformed from a wide format to a long format to facilitate time series analysis.
Date Creation: A 'Date' column was created to represent the time series correctly.
Handling Missing Values: Missing data points were filled using forward and backward filling methods.
Visualization techniques were employed to explore trends and patterns in the data.

## Model Training and Testing
Three different time series models were used to forecast the revenue:

## Exponential Smoothing
ARIMA (AutoRegressive Integrated Moving Average)
Prophet
The data was split into training and testing datasets to evaluate the performance of each model.

Model Comparison and Selection
The models were compared based on their performance using the Root Mean Square Error (RMSE) metric. The best-performing model was selected for forecasting future revenues.

## Forecasting
The selected model (ARIMA) was used to make future revenue predictions for the medical device companies. The forecasted results are visualized to show the expected trends within the next 8 quarters (2 years).
