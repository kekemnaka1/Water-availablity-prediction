# Water Availability Prediction Using AI
**Arizona State University | Academic Research | 2024–2025**

## Overview
Built predictive machine learning models for water availability forecasting 
using large-scale hydrological time-series datasets. The CNN-LSTM architecture 
achieved R²=0.93, outperforming all baseline models including ARIMA, 
Holt-Winters, and traditional hydrological models.

## Key Results
- **CNN-LSTM (top performer):** R²=0.93, RMSE reduction of 44% vs best baseline
- **Nash-Sutcliffe Efficiency (NSE):** 0.94 vs 0.79 (HBV baseline)
- **Climate scenario analysis:** 38% reservoir reduction under severe stress scenario

## Technical Approach
- **Feature engineering:** Lag features (1h, 6h, 24h, 7d, 30d), rolling statistics, 
  cyclical encodings (sin/cos), Antecedent Precipitation Index (API)
- **Models evaluated:** CNN-LSTM, Random Forest, XGBoost, LSTM, Ensemble (stacking)
- **Sensitivity analysis:** Sobol indices — antecedent precipitation and soil moisture 
  account for 65%+ of forecast variance
- **Backtesting:** Evaluated across drought, wet, and intermediate hydrological regimes

## Stack
`Python` `TensorFlow` `Pandas` `NumPy` `Scikit-learn` `Matplotlib`

## Research Output
Co-authored peer-reviewed paper in Elsevier Big Data Research format covering 
methodology, statistical findings, and environmental policy implications.
