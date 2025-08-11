# Stock-Predictor-LTBR-

A Data Science Project in Python to predict the stock price of Lightbridge Corporation, a nuclear energy company.

Tools Used:
  - Pandas, Numpy
  - Scikit-learn
  - Matplotlib
  - Xgboost

This project encompasses:
  - Data extraction. Data set taken from yahoo finance (last 6 years of relevent stock data
  - Data cleaning. Dropping any Nan within dataframes values with Pandas
  - Manipulating data. Generates and uses closing price ratios over two days, five days, etc. from existing data
  - Analysis. Uses XGBoost to Classify whether or not the stock price will increase or decrease.
  - Testing. Build a backtesting system (situates the model in the past, testing it on years of 'future data')

Results:
  - Initial precision score of the model: 35%
  - Final precision score of the model: 54%
