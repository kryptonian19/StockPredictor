# Stock Price Prediction using LSTM and RNN

This project predicts future stock prices using **Long Short-Term Memory (LSTM)** neural networks. It features a **Flask web application** that allows users to select a stock from a predefined list, view its past performance, and predict its future prices. The predictions are displayed in a visually appealing table and graph format.

## Features

- Select from a list of popular stocks (e.g., AAPL, AMZN, TSLA).
- View a graph of past performance and future predictions.
- Train models dynamically for stocks that haven't been pre-trained.
- Display predicted stock prices in a table and graph format.
- Interactive UI with hover effects for better user experience.

## Tech Stack

- **Frontend**: HTML, CSS (with hover effects)
- **Backend**: Python (Flask framework)
- **Machine Learning**: LSTM Neural Network (Keras, TensorFlow)
- **Data Source**: Yahoo Finance API (via `yfinance` library)
- **Graphing**: Matplotlib for visualizing predictions

---

## Project Structure

```plaintext
stock_price_prediction/
├── app.py                 # Flask backend and ML logic
├── templates/
│   ├── index.html         # Homepage for selecting stocks
│   ├── results.html       # Results page with predictions and graph
├── static/
│   ├── style.css          # CSS styling
│   ├── graph.png          # Graph image of predicted stock prices
├── requirements.txt       # Project requirements
