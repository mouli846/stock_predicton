# stock_predicton
# Stock Price Prediction

This project aims to predict future stock prices using historical data and various machine learning techniques. The dataset includes historical stock prices of Tata, which is processed and analyzed for predictions. The project involves data preprocessing, visualization, and predictive modeling using Python.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Dependencies](#dependencies)
- [License](#license)

## Overview
The goal of this project is to predict future stock prices based on historical price data. Several machine learning models are explored to predict stock closing prices, with a focus on time-series forecasting.

## Dataset
The dataset contains the following features:
- **Date**: The date of the stock data
- **Open**: The opening price of the stock on that day
- **High**: The highest price of the stock on that day
- **Low**: The lowest price of the stock on that day
- **Close**: The closing price of the stock on that day
- **Adjusted Close**: The closing price adjusted for splits and dividends
- **Volume**: The number of shares traded on that day

## Project Workflow
1. **Data Collection**: Stock price data is loaded from a CSV file.
2. **Data Preprocessing**: Data is cleaned, formatted, and transformed. Missing values are handled, and the 'Date' column is converted to datetime format.
3. **Exploratory Data Analysis (EDA)**: Visualization of stock trends using libraries like `matplotlib` and `plotly`. Key patterns and outliers are identified.
4. **Feature Engineering**: Additional features, such as moving averages and stock returns, are computed to improve prediction accuracy.
5. **Modeling**: Various models are built to predict stock prices, including:
   - Linear Regression
   - Decision Trees
   - Random Forest
   - LSTM (Long Short-Term Memory) Neural Networks
6. **Evaluation**: Models are evaluated using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
7. **Prediction**: The best-performing model is used to predict future stock prices.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mouli846/stock-price-prediction.git
