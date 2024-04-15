# stock-prediction-rnn
# Overview
This project implements a Recurrent Neural Network (RNN) using TensorFlow and Keras to predict stock prices. It demonstrates the use of LSTM (Long Short-Term Memory) networks to model sequential data for forecasting the future values of stock prices. The model is trained on historical stock price data fetched via the Yahoo Finance API.

# Features
**Data Fetching**: Utilizes *yfinance* to download historical stock data.

**Data Preprocessing**: Employs MinMaxScaler for scaling the stock prices to a normalized range, which is crucial for the performance of neural networks.

**Model Building**: Constructs an LSTM-based model to predict stock prices. The model includes dense layers and LSTM layers optimized for sequence prediction.

**Visualization**: Provides visualizations for training results and predictions using *matplotlib*, helping users evaluate the model's performance.

#Installation
To run this project, ensure you have Python installed, then set up a virtual environment and install the required packages:

`pip install -r requirements.txt`

# Usage
**Open Notebook**: Load the stock_prediction_rnn.ipynb notebook in Jupyter or Google Colab.

**Run All Cells**: Execute the cells sequentially to fetch data, train the model, and view the results.

# Contributions
Contributions are welcome! Please create a pull request or issue to suggest improvements or add new features.
