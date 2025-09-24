# ML Finance Portfolio Project

## Objective
Predict daily excess returns of US & Indian stocks using machine learning and create a probability-weighted trading strategy with risk-adjusted performance metrics.

## Data
- US Stocks: AAPL, MSFT, TSLA (Benchmark: S&P 500)
- Indian Stocks: RELIANCE.NS, INFY.NS (Benchmark: Nifty 50)
- Macro Features: VIX, 10Y Treasury yield, USD/INR exchange rate

## Features
- Technical Indicators: Moving averages (5,10,20 days), volatility, momentum  
- Macro Indicators: Market volatility, yield, exchange rate  

## Models
- XGBoost classifier predicting positive/negative excess returns  
- Probability-weighted portfolio strategy  
- Multi-stock backtesting with stop-loss/take-profit rules  

## Results
- Directional Accuracy: ~76%  
- Weighted Portfolio Sharpe Ratio: 0.11  
- Maximum Drawdown: -11.18%  

## Visualizations
- Cumulative returns vs benchmark  
- Feature importance (top 20 indicators)  

## Tech Stack
Python, pandas, numpy, scikit-learn, xgboost, yfinance, matplotlib, Google Colab

## How to Run
1. Install dependencies: `pip install -r requirements.txt`  
2. Open `finance_ml_project.ipynb` in Google Colab  
3. Run all cells sequentially  
