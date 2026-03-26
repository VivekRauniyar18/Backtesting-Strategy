# Backtesting-Strategy

# Moving Average Crossover Backtesting

This is a simple project where I tried to understand how backtesting works in quantitative finance.

I used a basic moving average crossover strategy and tested it on historical SPY data.

---

## What I did

- Pulled historical price data using yfinance  
- Calculated 20-day and 200-day moving averages  
- Generated buy/sell signals based on crossover  
- Simulated trades and tracked profit/loss  
- Plotted cumulative returns  

## Strategy idea

The idea is pretty simple:

- Buy when short-term trend (20-day MA) goes above long-term trend (200-day MA)  
- Sell when it goes below  

This is a common trend-following strategy.

## What I learned

- How to work with financial time series data  
- How backtesting helps check if a strategy works  
- Even simple strategies can behave very differently over time  
- Risk matters, not just returns  

## Limitations

This is a beginner project, so there are definitely things that can be improved:

## What I want to improve next

- Add Sharpe ratio and max drawdown  
- Compare with benchmark  
- Try different strategies  

## Final thoughts

This project helped me understand how trading strategies are tested before using real money.

Still learning and exploring more in quant finance.
