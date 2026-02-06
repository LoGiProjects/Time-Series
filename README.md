# Time-Series
Time-Series MSIT Project

## Project Overview
In this project we take a closer look at the Corporación Favorita Grocery Sales Forecasting Datasets.
We filter and prepare data to fit the following criteria:
- Region: Guayas
- Product Families: Top 3 (Grocery I, Beverages, Cleaning)
- Time Range: Jan 01 2013 – March 31 2014
- Target Variable: Unit_sales

This leaves us with roughly 2,750,000 records

## Project Key Features
- Exploratory Data Analysis
- Forecasting using ARIMA, XGBoost, Holt-Winters and Prophet
- Insights
- Recommendation / Reflection

## Model Comparisons

Evaluation Matrix
-MSE
-RMSE
-RMSLE
-MAE

Model________ RMSLE__	RMSE___	MSE________ MAE_____ Training Time
XGBoost______ 0.03___ 0.41___ 0.17_______ 0.02____	6.53
ARIMA_______	0.43___ 0.98__	0.95_______ 0.46____ 73.64
Holt-Winters	7.29___ 2948.84 8695643.37_ 2553.83_ 450.48
