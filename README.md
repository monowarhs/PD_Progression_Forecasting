# Parkinson's Disease Progression Forecasting with LSTM

## Overview
This project forecasts Parkinson’s disease progression by predicting UPDRS (Unified Parkinson’s Disease Rating Scale) scores over time using an LSTM neural network. 

**Dataset**: [Parkinson’s Telemonitoring Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring)  

**Model**: Long Short-Term Memory (LSTM) network for time-series forecasting.

## Key Features
- **Time-Series Analysis**: Models UPDRS progression across multiple patient visits.
- **MinMax Scaling**: Normalizes features for stable LSTM training.
- **Progressive Forecasting**: Predicts future UPDRS scores using past 3 visits’ data.
- **Visualization**: Compares true vs. predicted UPDRS trajectories.

## Prerequisites
- Python 3.8+
- Libraries: `numpy`, `pandas`, `tensorflow`, `scikit-learn`, `matplotlib`
