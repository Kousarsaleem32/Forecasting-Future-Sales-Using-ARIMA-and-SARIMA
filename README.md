# Champagne Sales Forecasting with ARIMA and SARIMA

This project focuses on time series forecasting of monthly champagne sales using **ARIMA** and **Seasonal ARIMA (SARIMA)** models.

## Overview

- **Dataset:** `perrin-freres-monthly-champagne.csv`
- **Goal:** Forecast future champagne sales using statistical time series models
- **Models Used:** ARIMA, SARIMA
- **Tools:** `pandas`, `matplotlib`, `statsmodels`

## Key Steps

1. Data preprocessing and handling missing values
2. Time series decomposition (trend, seasonality, residual)
3. Stationarity testing with Augmented Dickey-Fuller test
4. Model selection using AIC and residual analysis
5. Forecasting with:
   - **ARIMA**
   - **SARIMA**

## Results

- **SARIMA** as expected captured seasonal patterns better and gave more accurate forecasts than simple ARIMA.
- Forecast plots show model fit and prediction horizon.

## Dataset

- Source: Monthly sales data for Perrin Frères champagne
- Time range: 1964–1972
 
