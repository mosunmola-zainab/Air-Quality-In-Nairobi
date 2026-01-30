# Air Quality Time Series Forecasting - Nairobi, Kenya

Predictive modeling of PM2.5 air pollution levels using AutoRegressive and ARIMA time series models.

## Project Overview
Developed time series forecasting models to predict hourly PM2.5 air pollution levels in Nairobi to support public health monitoring and environmental decision-making.

## Key Results
- **MAE: 1.4** (Mean Absolute Error on test data)
- **64% improvement** over baseline
- **10,000+ hourly measurements** processed from MongoDB

## Technologies Used
- **Python:** Pandas, NumPy, Statsmodels, Scikit-learn
- **Modeling:** AutoRegressive (AR), ARIMA
- **Visualization:** Plotly, Matplotlib, Seaborn
- **Database:** MongoDB

## Methodology
1. Data retrieval from MongoDB database
2. Time series preprocessing and aggregation
3. Exploratory data analysis and visualization
4. Model development (AR, ARIMA)
5. Walk-forward validation
6. Hyperparameter tuning (grid search across 12 ARIMA configurations)

## Model Performance
| Model | MAE | Configuration |
|-------|-----|---------------|
| Baseline | 3.89 | Mean prediction |
| AutoReg | 1.4 | 26 lags |
| ARIMA | 1.67 | (8, 0, 1) |

## Setup & Usage
```bash
# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/air_quality_nairobi.ipynb
```

## Data Source
Air quality sensor data from Nairobi monitoring stations (2018).

## Author
Zainab Hassan
