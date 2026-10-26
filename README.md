# Automated Portfolio Risk & Performance Analyzer

Fetches live stock data and generates a full risk/performance report in seconds. Built for banking and fintech applications.

## 🚀 What it does
- Pulls adjusted stock prices via `yfinance`
- Computes annualized return, volatility, Sharpe ratio, max drawdown, Beta, Alpha, and VaR/CVaR
- Outputs a text report and a 4-panel chart (growth, drawdown, return distribution, rolling volatility)

## 📊 Sample Output
*(Once you run the code, upload your chart here and type: `![Portfolio Chart](portfolio_analysis.png)`)*

## 🛠️ How to Run
1. Install dependencies:
```bash
pip install yfinance pandas numpy matplotlib scipy
