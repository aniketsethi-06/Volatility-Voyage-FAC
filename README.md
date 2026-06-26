## 📌 Project Overview

The project aims to develop volatility-aware trading strategies and optimize investment decisions using statistical models, technical indicators, and portfolio management techniques. Multiple forecasting models were implemented and evaluated through backtesting to analyze risk-adjusted performance.

---

## 🚀 Features

- Exploratory Data Analysis (EDA) on historical market data
- Technical Indicators (SMA, EMA, ATR, MACD)
- EMA Crossover Strategy
- EMA + Dynamic Band Strategy
- ATR Breakout Strategy
- Dynamic Capital Allocation using India VIX
- Portfolio Optimization using Efficient Frontier
- Volatility Forecasting using EWMA, AR, ARMA, ARIMA, GARCH, and EGARCH
- Risk Management using Stop Loss, Take Profit, and Drawdown Control
- Capital-Neutral Long–Short Hedging Strategy
- Complete Backtesting Framework with Performance Evaluation

---

## 📂 Project Workflow

```
Historical Market Data
        │
        ▼
 Exploratory Data Analysis
        │
        ▼
 Technical Indicators
        │
        ▼
 Trading Signal Generation
        │
        ▼
 Risk Management
        │
        ▼
 Backtesting
        │
        ▼
 Performance Evaluation
        │
        ▼
 Volatility Forecasting
        │
        ▼
 Portfolio Optimization
        │
        ▼
 Hedging Strategy
```

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries
- NumPy
- Pandas
- Matplotlib
- SciPy
- Statsmodels
- yfinance
- arch

### Financial Concepts
- Efficient Frontier
- CAPM
- Sharpe Ratio
- Sortino Ratio
- VaR & CVaR
- Portfolio Optimization
- Volatility Forecasting

---

## 📊 Trading Strategies

### EMA Crossover
Generated buy and sell signals using Exponential Moving Average crossovers.

### EMA + Dynamic Band
Enhanced EMA crossover strategy by incorporating adaptive volatility bands.

### ATR Breakout
Used Average True Range (ATR) to identify dynamic breakout opportunities.

---

## ⚠️ Risk Management

Implemented multiple risk control techniques including:

- Trailing Stop Loss
- ATR-Based Stop Loss
- Take Profit
- Drawdown Exit
- Time-Based Exit
- Dynamic Position Sizing using India VIX

---

## 📈 Performance Metrics

Trading strategies were evaluated using:

- Net Profit
- Gross Profit
- Sharpe Ratio
- Sortino Ratio
- Maximum Drawdown
- Win Rate
- Holding Period
- Trade Statistics

---

## 📉 Volatility Forecasting Models

Implemented and compared:

- Rolling Volatility
- EWMA
- AR(1)
- ARMA
- ARIMA
- GARCH
- EGARCH

---

## 📊 Portfolio Optimization

Implemented:

- Mean-Variance Optimization
- Efficient Frontier
- Minimum Variance Portfolio
- Tangency Portfolio
- Volatility-Based Capital Allocation
- Portfolio Backtesting

---

## 🛡️ Hedging Strategy

Designed a Capital-Neutral Long–Short strategy by:

- Selecting stocks using EGARCH forecasts
- Identifying highly correlated hedge assets
- Building equal-capital long and short positions
- Reducing systematic market risk while preserving alpha

---

## 📚 Key Learnings

- Financial Time-Series Analysis
- Algorithmic Trading
- Volatility Forecasting
- Quantitative Risk Management
- Portfolio Optimization
- Statistical Modelling
- Backtesting Framework Design
- Market-Neutral Hedging

---
