# predict-usa-stocks-closing-movements
DS 677 Deep Learning : Predict USA Stocks Closing Movements

[kaggle Link](https://www.kaggle.com/competitions/optiver-trading-at-the-close/overview)

This project aims to develop a model to predict realized volatility in financial markets. Using high-frequency market data, the goal is to improve the efficiency and accuracy of trading strategies by forecasting price movements more effectively.

## Objective

The primary objective is to predict the realized volatility of financial assets using historical high-frequency data. This involves preprocessing large datasets, feature engineering, and implementing various machine learning models to enhance prediction accuracy.

## Project Overview

- **Data Preprocessing**: Data cleaning and feature engineering to extract meaningful features from raw stock trading data.
- **Model Development**: Implementation and evaluation of various machine learning models to predict realized volatility, including:
  - **Basic LSTM Model**: A simple LSTM network for capturing temporal dependencies in the data.
  - **Enhanced LSTM Model**: A more complex Bidirectional LSTM with additional Dense layers, batch normalization, and dropout for improved performance.
  - **CNN-LSTM Hybrid Model**: Combining 1D Convolutional layers for spatial feature extraction with LSTM layers for temporal dynamics.
- **Model Evaluation**: Comparison of models based on their test loss:
  - **Enhanced LSTM**: Test Loss = 89.5646 
  - **CNN-LSTM Hybrid Model**: Test Loss = 89.5636 
  - **Basic LSTM**: Test Loss = 89.5621 

## Conclusion

The models were evaluated based on their ability to predict realized volatility. The basic LSTM model, despite its simplicity, provided the best performance, highlighting the importance of feature engineering and data quality in predictive modeling for financial data.
