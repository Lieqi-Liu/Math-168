# Math168 Stock Prediction Project

This repository contains a Google Colab notebook and dataset for stock price analysis, stock relationship networks, and prediction model comparison.

## Repository Structure

- `Math168.ipynb` — main notebook with all code
- `stockData.csv` — stock price dataset used in the notebook

## What the Notebook Does

The notebook:
- loads and preprocesses stock data
- computes and plots 100-day moving averages
- trains a Linear Regression model
- builds stock relationship networks using correlation, lift, and Granger methods
- trains and evaluates GNN, LSTM, LSTM-GNN, and attention-based models
- compares model performance using MSE and visualizations

## How to Run

1. Open `Math168.ipynb` in Google Colab or Jupyter.
2. Make sure `stockData.csv` is in the same working directory.
3. Run the cells in order from top to bottom.

## Note
This notebook was created in Google Colab. If needed, change file paths like:
'''python
pd.read_csv('/content/stockData.csv')
'''
to 
'''python
pd.read_csv('stockData.csv')
'''
