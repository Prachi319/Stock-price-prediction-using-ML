# 📈 Stock Price Prediction using Machine Learning

This project focuses on building machine learning models to predict future stock prices using **Support Vector Machines (SVM)** and **Linear Regression**. It involves collecting historical stock data, performing data preprocessing and visualization, training models, and evaluating their predictive performance.

---

## 🔍 Project Overview

* **Goal**: Predict the future closing price of a stock based on historical data.
* **Tech Stack**: Python, scikit-learn, pandas, NumPy, matplotlib, seaborn
* **ML Models Used**:

  * Support Vector Regression (SVR)
  * Linear Regression

---

## 📊 Features

* Historical data download using `yfinance`
* Data preprocessing (feature engineering, scaling)
* Model training and testing on real-world stock data
* Price trend visualization
* Performance metrics for evaluation (MAE, MSE, R²)

---

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/stock-price-prediction-ml.git
   cd stock-price-prediction-ml
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## 📁 Project Structure

```
├── data/                 # Folder for storing stock data
├── notebooks/            # Jupyter notebooks for exploration and modeling
├── models/               # Saved models (optional)
├── stock_prediction.py   # Main script (if used)
├── README.md
└── requirements.txt
```



## 🧠 Machine Learning Models

### 1. Linear Regression

* Simple and interpretable baseline model
* Captures linear trends in price movements

### 2. Support Vector Regression (SVR)

* Captures nonlinear relationships
* Effective in handling outliers and small datasets

---

## 🚀 How to Use

1. Choose a stock symbol (e.g., `'AAPL'`, `'RELIANCE.NS'`).
2. Run the notebook or script to download data, train models, and visualize predictions.
3. Modify the forecast window (`n_days`) as needed.

---

## 📌 Future Improvements

* Include other models (LSTM, XGBoost)
* Add more features (technical indicators, volume, sentiment)
* Build a web dashboard using Streamlit

---

## 📚 References

* [Yahoo Finance API](https://pypi.org/project/yfinance/)
* [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)


