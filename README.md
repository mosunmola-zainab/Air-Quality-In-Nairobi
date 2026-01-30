# Air Quality Time Series Forecasting (Nairobi)

Predictive modeling of PM2.5 air pollution levels using AutoRegressive and ARMA models.

## Key Results
- **MAE: 1.4** (Mean Absolute Error)
- **64% improvement** over baseline
- **10,000+ hourly measurements** analyzed

## Technologies
Python, Pandas, NumPy, Statsmodels, Scikit-learn, Plotly, MongoDB

## Methodology
1. Data retrieval from MongoDB database
2. Time series preprocessing and aggregation
3. AutoRegressive and ARMA model development
4. Walk-forward validation
5. Hyperparameter tuning via grid search

## Data Source
Air quality sensor data from Nairobi monitoring stations (2018), accessed via MongoDB.

## Setup
```bash
pip install -r requirements.txt
jupyter notebook
```

## Author
Zainab Hassan
