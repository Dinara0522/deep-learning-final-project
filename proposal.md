# Project Proposal: Electricity Load Forecasting

## 1. Project Title
Short-Term Electricity Load Forecasting using LSTM and GRU Networks

## 2. Problem Statement
I aim to predict hourly electricity consumption. This is critical for energy providers to balance supply and demand. The model will predict consumption in Megawatts (MW).

## 3. Dataset
- **Name:** PJM Hourly Energy Consumption
- **Source:** https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption
- **Size:** ~145,000 hourly observations.

## 4. Planned Method
- **Baseline:** Linear Regression or simple MLP.
- **Deep Learning Model:** LSTM (Long Short-Term Memory).
- **Loss Function:** MSE.
- **Metrics:** MAE, RMSE.

## 5. Expected Challenges
Seasonality effects, handling outliers, and hyperparameter tuning for LSTM.

## 6. Weekly Plan
- **Week 1:** Proposal, Repository setup, EDA.
- **Week 2:** Preprocessing and Baseline model.
- **Week 3:** DL model training (LSTM/GRU).
- **Week 4:** Evaluation and Final Report.
