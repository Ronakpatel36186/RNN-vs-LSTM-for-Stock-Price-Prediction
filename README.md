# RNN vs LSTM Stock Price Prediction

## Overview
This project compares the performance of **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)** models for stock price prediction using historical market data.

The goal is to understand how different sequential deep learning architectures perform on time-series forecasting tasks.

---

## Stocks Analyzed
- Apple(AAPL)
- Tesla(TSLA)
- Amazon (AMZN)

data is fetched using Yahoo Finance API.

---

## Problem Statement
Predict the next day’s stock closing price using the previous **180 days of historical prices** and compare:
- Simple RNN performance
- LSTM performance

---

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- yfinance

---

## Pipeline Architecture

1. Data Collection (Yahoo Finance)
2. Data Preprocessing (Scaling + Windowing)
3. Train-Test Split (80/20)
4. Model Training:
   - Simple RNN
   - LSTM
5. Prediction on Test Data
6. Model Evaluation (RMSE)
7. Visualization of Results

---

## Model Architectures

### RNN
- Simple recurrent layer
- Struggles with long-term dependencies

### LSTM
- Uses gated memory mechanism
- Better at capturing long-term patterns in stock data

--- 

## Evaluation Metric
Model performance is evaluated using:

- **Root Mean Squared Error (RMSE)**

Lower RMSE indicates better prediction accuracy.

---

## Key Results (Observation)
- LSTM consistently outperforms RNN
- RNN struggles with long-term dependency in stock trends
- LSTM provides smoother and more accurate predictions

---

## Visualization
The project includes comparison plots showing:
- Actual stock prices
- RNN predictions
- LSTM predictions

---

## How to Run

### Install dependencies
```bash
pip install -r requirements.txt
```

---

## Learning Outcomes
- Understanding of sequential deep learning models
- Hands-on experience with RNN and LSTM
- Time-series forecasting pipeline design
- Model evaluation using RMSE
- Real-world financial data handling

## Author

Ronak Patel
Master’s in Computer Science
Interested in Machine Learning, Deep Learning, and AI systems

Thank you