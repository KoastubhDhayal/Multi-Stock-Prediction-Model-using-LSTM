# Multi-Stock-Prediction-Model-using-LSTM
This project implements a deep learning model for stock price prediction using Long Short-Term Memory (LSTM) neural networks. The model analyzes historical stock market data and learns temporal patterns to predict future stock prices.

The system preprocesses stock market features such as Open, High, Low, Close prices and Volume, and trains an LSTM-based neural network to capture sequential dependencies in financial time series data.

This project demonstrates the application of deep learning for financial forecasting and time series analysis.

Features

Stock price prediction using LSTM neural networks

Time-series sequence generation

Data normalization using MinMaxScaler

Multi-stock support using label encoding

Early stopping for optimized training

Visualization of prediction results

End-to-end deep learning workflow

Technologies Used
Programming Language

Python

Libraries

NumPy

Pandas

Scikit-learn

TensorFlow / Keras

Matplotlib

Deep Learning Architecture

LSTM (Long Short-Term Memory)

Dense Layers

Dropout for regularization

Dataset

The project uses a dataset containing stock market information with the following features:

Feature	Description
Date	Trading date
Stock	Stock identifier
Open	Opening price
High	Highest price
Low	Lowest price
Close	Closing price
Volume	Trading volume
Machine Learning Pipeline
1 Data Preprocessing

Convert date column to datetime

Encode stock names using LabelEncoder

Normalize features using MinMaxScaler

2 Sequence Generation

Time series sequences are generated using a sliding window approach.

Sequence length: 30 time steps

Each sequence represents past stock behavior

3 Model Architecture

The neural network consists of:

LSTM layers for sequential learning

Dropout layers to prevent overfitting

Dense layers for prediction output

This architecture helps the model capture temporal dependencies in stock price movements.

Model Training

Training is performed using:

Train-test split

Early stopping to prevent overfitting

Backpropagation using TensorFlow

The model learns patterns from historical stock data to predict future closing prices.
