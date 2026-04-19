                              # Predictive-Analytics-for-Forex-Market-Behavior
A machine learning and deep learning based project for forecasting forex market trends using time series analysis and predictive analytics.
# Predictive Analytics for Forex Market Behaviour

## Overview
This project investigates statistical, machine learning, and deep learning approaches for forecasting forex market behavior. The objective is to model and predict time series dynamics of currency pairs (e.g., EUR/USD) using historical data.

The work focuses on comparative analysis across multiple modeling paradigms to evaluate their ability to capture temporal dependencies, seasonality, and nonlinear patterns.

---

## Problem Statement
Forex markets are difficult to model due to:
- High volatility and noise
- Non-stationary behavior
- Complex temporal dependencies
- Influence of external factors

This project applies a range of models to address these challenges and evaluate predictive performance.

---

## Dataset
- Type: Time series (hourly data)
- Example: EUR/USD exchange rate
- Features:
  - Open, High, Low, Close
  - Lag features
  - Rolling statistics

Note: Dataset is not included due to size constraints. Place your dataset in the `/data` directory.

---

## Models Applied

### Statistical Models
- AutoRegressive (AR) Model (AutoReg)
- Moving Average (MA) Model (ARIMA(0,0,q))
- AutoRegressive Moving Average (ARMA) Model (ARIMA(p,0,q))
- AutoRegressive Integrated Moving Average (ARIMA(p,d,q))
- Seasonal ARIMA (SARIMA) with seasonal period s = 24
- SARIMAX (with exogenous variables)

---

### Machine Learning Models
- Random Forest Regressor
- XGBoost Regressor
- LightGBM Regressor


---

### Neural Network Models
- Multi-Layer Perceptron (MLP)
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Temporal Convolutional Network (TCN)

---

###Probabilistic Models
-Quantile regression
-Conformal prediction

---

### Advanced Deep Learning Models
- WaveNet
- N-BEATS
- Temporal Fusion Transformer (TFT)
- DeepAR
- XGBoost (used as baseline comparison)

---

## Feature Engineering
- Lag features
- Rolling statistics (mean, variance)
- Differencing for stationarity
- Seasonal decomposition

---

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

---

## Results
The project compares all models based on forecasting accuracy and generalization.

Deep learning models capture complex nonlinear relationships effectively, while statistical models provide strong interpretable baselines.

---

## Project Structure
