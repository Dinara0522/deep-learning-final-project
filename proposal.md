# Project Proposal: Electricity Load Forecasting

## 1. Project Title
Short-Term Electricity Load Forecasting using LSTM and GRU Networks

---

## 2. Problem Statement
The goal of this project is to predict future electricity consumption based on historical time series data.

Accurate forecasting is important for energy providers to optimize resource allocation and maintain grid stability.

The model will take a sequence of past hourly electricity consumption values as input and predict the next hour’s load in Megawatts (MW).

---

## 3. Dataset

- **Name:** PJM Hourly Energy Consumption  
- **Source:** https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption  
- **Size:** ~145,000 hourly observations  

### Features:
- Datetime (timestamp)
- Electricity load (MW)

### Target:
- Future electricity load (next hour prediction)

### Data Format:
- Time series data (CSV)

### Data Processing Plan:
- Extract time-based features (hour, day, month)
- Create sequences (e.g., last 24 hours → next hour)
- Split dataset:
  - Train: 70%
  - Validation: 15%
  - Test: 15%

---

## 4. Planned Method

### Baseline:
- Linear Regression or simple MLP

### Deep Learning Models:
- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)

### Loss Function:
- Mean Squared Error (MSE)

### Evaluation Metrics:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

---

## 5. Expected Challenges

- Strong seasonality patterns (daily and yearly)
- Presence of outliers in electricity consumption
- Risk of overfitting due to temporal dependencies
- Hyperparameter tuning for LSTM and GRU models
- Computational cost of training sequence models

---

## 6. Weekly Plan

| Week | Planned Work | Expected Output |
|------|-------------|----------------|
| Week 1 | Dataset selection, repository setup, exploratory data analysis (EDA) | Proposal, dataset summary, visualizations |
| Week 2 | Data preprocessing, sequence creation, baseline model | Baseline results |
| Week 3 | LSTM and GRU model training and tuning | Model results, loss curves |
| Week 4 | Model improvement, evaluation, final report | Final metrics, report, visualizations |
