# Financial Time Series Analysis and Forecasting

## Overview
This project analyses and models equity price data using both classical statistical methods and exploratory machine learning approaches. The goal is to understand temporal dependencies in financial data and evaluate forecasting techniques.

---

## Dataset
- Asset: Hindustan Unilever Ltd. (HUL)
- Frequency: Daily prices  
- Period: Jan 2015 – Jul 2025  

---

## Objectives
- Analyse trends, seasonality, and non-stationarity in financial time series  
- Build statistical and machine learning models for forecasting  
- Compare classical and data-driven approaches  

---

## Methodology

### 1. Exploratory Analysis
- Trend and return analysis  
- Decomposition into components  

### 2. Stationarity Testing
- Augmented Dickey-Fuller (ADF) test  
- Differencing and transformations  

### 3. Models Applied
- ARIMA  
- SARIMA  
- Exponential Smoothing
- LSTM  

### 4. Model Selection
- Based on AIC/BIC, residual diagnostics, and forecast performance  

---

## Results
- ARIMA/SARIMA models provided stable baseline forecasts  
- LSTM captured certain non-linear patterns but required larger data for consistent performance  

---

## Key Insights
- Financial time series are highly non-stationary  
- Classical models provide interpretable baselines  
- Deep learning approaches may capture non-linear dependencies but are sensitive to data and hyperparameters  
- Market volatility and shocks remain difficult to model  

---

## Tech Stack
- Python  
- pandas, numpy  
- statsmodels  
- TensorFlow / Keras  
- matplotlib

---
