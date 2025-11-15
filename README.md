# Short-Term Stock Price Prediction

## Project Summary
This project demonstrates a simple approach to **predicting the next-day closing price of a stock** using historical stock data. We used **Apple Inc. (AAPL)** as an example and applied two regression models: **Linear Regression** and **Random Forest Regressor**. The goal is to compare model performance and visualize actual vs predicted stock prices.

---

## Technologies & Libraries
- **Python Libraries:**
  - `yfinance` – download historical stock data
  - `pandas` & `numpy` – data manipulation
  - `matplotlib` & `seaborn` – visualization
  - `scikit-learn` – regression modeling and evaluation

---

## Dataset
- **Source:** Yahoo Finance (via `yfinance`)
- **Stock:** Apple Inc. (`AAPL`)
- **Date Range:** 2020-01-01 to 2025-01-01
- **Columns:** `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`
- **Target:** Next-day closing price (`Close` column shifted by one row)
