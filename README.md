📈 Tesla Stock Price Prediction using LSTM

This project focuses on predicting Tesla’s stock price using Long Short-Term Memory (LSTM), a deep learning model well-suited for time series forecasting. The workflow includes Exploratory Data Analysis (EDA), data preprocessing, model building, and evaluation to assess prediction accuracy.

🚀 Project Overview:

  Collected Tesla stock price dataset (time series).
  Performed EDA to understand trends, seasonality, and price movement patterns.
  Preprocessed data (scaling, feature engineering, train-test split).
  Built and trained an LSTM model for stock price prediction.
  Evaluated the model’s performance using metrics such as RMSE, MAE, MSE, and R².

🛠️ Tech Stack

Programming Language: Python
Libraries & Frameworks:
  pandas, numpy → Data preprocessing & manipulation
  matplotlib, seaborn → Data visualization & EDA
  scikit-learn → Scaling & evaluation metrics
  tensorflow / keras → Building & training LSTM model

📊 Workflow

Data Collection:
  Used Tesla stock historical data (can be downloaded via Yahoo Finance or yfinance library).

Exploratory Data Analysis (EDA):
  Visualized stock price trends, volume, and moving averages.
  Checked stationarity and correlations between features.

Data Preprocessing:
  Handled missing values (if any).
  Normalized stock price values using MinMaxScaler.
  Converted time series data into supervised learning format for LSTM input.

Model Building (LSTM):
  Designed a sequential model with stacked LSTM layers.
  Added Dropout layers to prevent overfitting.
  Used Adam optimizer and Mean Squared Error (MSE) loss function.

Model Evaluation:
  Compared predicted vs actual stock prices.
  Metrics used: RMSE, MAE, R².

📈 Results:
  The LSTM model was able to capture stock price patterns and trends.
  Predictions closely followed actual Tesla stock prices with minimal error.

The LSTM model was able to capture stock price patterns and trends.
Predictions closely followed actual Tesla stock prices with minimal error.
