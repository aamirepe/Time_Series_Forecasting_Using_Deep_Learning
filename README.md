# Time Series Forecasting Using Deep Learning

This repository contains deep learning models for time series forecasting, focused on stock price prediction using LSTM networks.

We use both univariate and multivariate approaches, applying Long Short-Term Memory (LSTM) models on Apple stock data to predict future `Close` prices.

---

## Features

- LSTM model with configurable input window
- Univariate and multivariate input support
- Train, validation, and test splitting with clear visualizations
- Scaled and inverse-scaled predictions
- Evaluation metrics and loss plots

---

## Project Structure

```bash
├── data/                         # (Optional) Folder for datasets
├── notebooks/
│   ├── univariate_lstm.ipynb     # Forecasting using only 'Close' prices
│   └── multivariate_lstm.ipynb   # Forecasting using multiple stock features
├── plots/                        # Output figures (optional)
├── model/                        # Saved models (optional)
└── README.md                     # Project overview
