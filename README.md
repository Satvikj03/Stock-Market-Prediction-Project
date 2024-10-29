# Stock Market Prediction for S&P 500 Index

This project predicts the price of the S&P 500 index using a machine learning model, specifically a Random Forest Classifier. The model aims to forecast future price movements based on historical data, including price and traded volume, to support better-informed trading decisions.

## Project Overview

The project involves several key steps:
1. **Data Collection**: Download historical data of the S&P 500 index, including price and volume, using the `yfinance` package.
2. **Model Development**: Create an initial machine learning model (Random Forest Classifier) to predict price direction.
3. **Performance Evaluation**: Implement a backtesting engine to test the model's accuracy and assess its predictive capabilities over historical data.
4. **Model Improvement**: Continuously refine the model to enhance its accuracy by experimenting with different parameters and adding new features.

## Tech Stack

The following libraries and tools were used in this project:
- **Python**: Programming language for data handling, model building, and backtesting.
- **Jupyter Notebook**: For writing and running code, visualizing data, and documenting the development process.
- **yfinance**: To download historical S&P 500 index data and other financial data.
- **Scikit-Learn**: Machine learning library used for model building and evaluation, specifically the Random Forest Classifier.
