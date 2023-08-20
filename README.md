# Stock Price Prediction using Scikit-Learn

This repository contains a simple example of using scikit-learn to perform stock price prediction. The program utilizes the `HistGradientBoostingRegressor` model from scikit-learn to predict stock prices based on various features such as Open, High, Low, Close, and Volume.

## Description

Stock price prediction is a common application of machine learning in finance. In this example, we demonstrate how to use scikit-learn, a popular machine learning library in Python, to predict stock prices using historical data. The program performs the following steps:

1. Load historical stock data from a CSV file.
2. Extract relevant features (Open, High, Low, Close, Volume) and the target variable (Adj Close).
3. Handle missing values using a simple method (dropping rows with missing values).
4. Split the dataset into training and testing sets.
5. Train a `HistGradientBoostingRegressor` model to predict stock prices.
6. Evaluate the model's performance using Mean Squared Error and R-squared metrics.

This example is meant to provide a starting point for those interested in exploring stock price prediction using machine learning.

## Usage

1. Clone this repository to your local machine using `git clone`.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Replace the actual path to your dataset file in the code.
4. Run the program using `python stock_price_prediction.py`.

## Dependencies

- Python 3.x
- scikit-learn
- pandas


