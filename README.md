# Cross-Asset Dependency Prediction System

An AI-powered financial analytics dashboard that predicts future stock returns using machine learning and cross-asset dependency analysis.

---

# Project Overview

This project learns relationships between multiple stocks and predicts future stock movements based on cross-stock dependencies.

The system uses:

- Machine Learning
- Financial Time-Series Analysis
- Cross-Asset Correlation
- Feature Engineering
- Dashboard Visualization

---

# Features

## Stock Return Prediction

Predicts next-period stock returns using Random Forest Regression.

---

## Cross-Asset Dependency Analysis

Analyzes relationships between stocks using correlation analysis and heatmaps.

---

## Ranked Outperformers & Underperformers

Ranks stocks based on latest returns.

---

## AI Dashboard

Interactive dashboard built using Flask.

Includes:

- Sidebar Navigation
- Prediction System
- Market Dashboard
- Dependency Heatmap
- Charts & Visualization

---

## Buy/Sell Signal

Generates AI-based:

- BUY 📈
- SELL 📉

signals.

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| Flask | Web Framework |
| Pandas | Data Processing |
| Scikit-learn | Machine Learning |
| Random Forest | Prediction Model |
| Seaborn | Heatmap Visualization |
| Matplotlib | Charts |
| Chart.js | Dashboard Graphs |
| Yahoo Finance API | Stock Data |

---

# Dataset Source

Stock market data collected using:

- Yahoo Finance API (`yfinance`)

Stocks Used:

- AAPL
- MSFT
- TSLA
- NVDA
- GOOGL
- AMZN

Time Period:

2020 - 2025

---

# Project Structure

```text
cross-asset-dependency-prediction/
│
├── app.py
├── README.md
├── requirements.txt
│
├── data/
│   ├── stocks.csv
│   ├── returns.csv
│   ├── features.csv
│   └── dependency_scores.csv
│
├── models/
│   └── stock_model.pkl
│
├── outputs/
│   └── evaluation.txt
│
├── static/
│   ├── style.css
│   ├── heatmap.png
│   └── dashboard.js
│
├── templates/
│   ├── index.html
│   ├── predict.html
│   ├── results.html
│   └── about.html
│
└── src/
    ├── data_collection.py
    ├── feature_engineering.py
    ├── dependency_analysis.py
    ├── model_training.py
    ├── evaluation.py
    └── ranking.py
