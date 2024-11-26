# Apple Stock Predictions Using LSTM

## Overview
This project focuses on forecasting Apple stock prices using **Long Short-Term Memory (LSTM)** neural networks. The goal is to leverage deep learning techniques to model and predict temporal patterns in stock price data, providing actionable insights for financial strategies.

## Features
- Data acquisition using **Yahoo Finance API** for Apple stock data.
- Feature engineering with technical indicators such as:
  - **RSI** (Relative Strength Index)
  - **EMA** (Exponential Moving Average)
- Data preprocessing, including **Min-Max scaling** for model optimisation.
- Implementation of an **LSTM-based deep learning model** with a 30-day lookback window.
- Evaluation metrics:
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
- Visualisations comparing predicted and actual stock prices.

## Tools and Technologies
- **Python**: Core programming language.
- **TensorFlow**: For building and training the LSTM model.
- **Pandas** and **NumPy**: For data manipulation and analysis.
- **Matplotlib**: For creating visualisations.
- **Yahoo Finance API**: For retrieving stock data.

## Project Pipeline
1. **Data Collection**: Historical stock price data was retrieved using Yahoo Finance API.
2. **Data Preprocessing**:
   - Handled missing values and resampled the data to ensure consistency.
   - Scaled features using Min-Max scaling.
3. **Feature Engineering**:
   - Added technical indicators (RSI, EMA) to enhance predictive accuracy.
4. **Model Development**:
   - Built an LSTM neural network to capture temporal dependencies in stock price trends.
5. **Evaluation and Visualisation**:
   - Evaluated the model using MSE, MAE, and RMSE.
   - Plotted predicted vs. actual prices for validation.

## Results
The model successfully captured stock price trends, providing insights into temporal dependencies and offering predictions applicable to financial decision-making and trading strategies.

## Future Work
- Incorporating additional features like macroeconomic indicators.
- Experimenting with other deep learning architectures, such as GRU or Transformer models.
- Deploying the model using a web interface for real-time predictions.
