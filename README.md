# 📈 BSE SENSEX Price Movement Prediction using Machine Learning

An end-to-end Machine Learning project that predicts stock market price movements using historical market data, technical indicators, and feature engineering. The project applies multiple machine learning models to classify the next day's market direction based on financial time-series data.

---

## 🚀 Project Overview

This project demonstrates a complete machine learning workflow for financial market prediction, including:

- Historical stock market data collection
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Technical Indicator Generation
- Machine Learning Model Development
- Model Evaluation and Performance Comparison

The primary objective is to predict whether the market will move **Up** or **Down** on the following trading day.

---

## 📊 Dataset

- **Source:** Yahoo Finance
- **Index:** S&P BSE SENSEX
- **Data:** Historical Daily OHLCV Prices
- **Period:** Multiple years of historical market data

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Plotly
- yFinance
- TA (Technical Analysis Library)
- Jupyter Notebook

---

## 📈 Technical Indicators

The following technical indicators were engineered as model features:

- Relative Strength Index (RSI)
- Moving Average Convergence Divergence (MACD)
- Signal Line
- MACD Histogram
- Simple Moving Averages (20, 50, 100, 200)
- Exponential Moving Averages (12, 26)
- Bollinger Bands
- Daily Returns
- Log Returns
- Rolling Volatility
- Cumulative Returns
- Drawdown
- Moving Average Crossovers

---

## 🤖 Machine Learning Models

The project compares the performance of multiple algorithms:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

---

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score
- Classification Report

---

## 📂 Project Structure

```
Stock-Market-Prediction-ML/
│
├── notebooks/
│   └── Stock_Market_Prediction.ipynb
│
├── data/
│   └── Dataset
│
├── images/
│   └── Visualizations
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📌 Workflow

1. Data Collection from Yahoo Finance
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Technical Indicator Calculation
6. Model Training
7. Model Evaluation
8. Performance Comparison

---

## 📷 Sample Visualizations

The notebook includes multiple visualizations such as:

- Candlestick Charts
- Moving Average Analysis
- RSI Analysis
- MACD Analysis
- Bollinger Bands
- Correlation Heatmap
- Feature Importance
- Confusion Matrix

---

## 🎯 Future Improvements

- LSTM-based Deep Learning Models
- Trading Strategy Backtesting
- Hyperparameter Optimization
- Model Deployment using Streamlit or Flask
- Real-Time Market Prediction

---

## 📜 License

This project is released under the MIT License.

---

## 👤 Author

**Aniket Chakroborty**

Aspiring Data Scientist | Machine Learning Enthusiast | Financial Analytics

GitHub: https://github.com/YOUR_USERNAME
