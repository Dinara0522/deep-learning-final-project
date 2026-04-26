# Weekly Report - Week 01

## Completed
- Selected project topic: Electricity Load Forecasting
- Defined problem as time series forecasting task
- Found and reviewed dataset (PJM Hourly Energy Consumption from Kaggle)
- Created project proposal
- Set up GitHub repository with required structure

## Repository Changes (Commits)
- Initialized repository structure (folders and README)
- Added project proposal
- Added week 01 report

## Dataset Exploration
- Inspected dataset format (time series with hourly timestamps)
- Identified main variable: electricity load (MW)
- Checked dataset size (~145,000 observations)
- Confirmed dataset suitability for forecasting task

## Results
- Dataset is appropriate for time series forecasting
- Data is sufficiently large for training deep learning models
- Problem formulation (sequence → next value prediction) is feasible

## Problems / Challenges
- Dataset is large and requires preprocessing
- Need to convert time series into sequences for model input
- Potential seasonality patterns need to be handled

## Plan for Next Week
- Perform data preprocessing (cleaning, normalization)
- Create input sequences (sliding window approach)
- Split dataset into train/validation/test sets
- Implement baseline model (Linear Regression or MLP)
