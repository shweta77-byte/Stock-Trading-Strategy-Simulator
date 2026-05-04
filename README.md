 Stock Trading Strategy Simulator

 Objective
To analyze stock market data and evaluate trading strategies using historical price data.



 Project Overview
This project simulates a stock trading strategy using historical market data.  
It applies technical indicators to generate buy and sell signals and evaluates performance through backtesting.



 Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- yfinance  



 Strategy Used
The strategy is based on Moving Average Crossover:

- Buy when **SMA20 > SMA50**
- Sell when **SMA20 < SMA50**



 Features
- Fetch historical stock data using yfinance  
- Data visualization using matplotlib  
- Calculation of technical indicators (SMA20, SMA50)  
- Automated buy/sell signal generation  
- Backtesting trading strategy  
- Comparison with buy-and-hold approach  



 Results

| Strategy Type | Final Value |
|--------------|------------|
| Strategy     | ₹11,704    |
| Buy & Hold   | ₹32,598    |



 Conclusion
The moving average crossover strategy underperformed compared to the buy-and-hold strategy.

This indicates that simple technical strategies may not perform well in strongly trending markets.



 Future Improvements
- Add RSI (Relative Strength Index)  
- Implement machine learning models for prediction  
- Optimize strategy parameters  
- Build an interactive dashboard (Streamlit)  



 Project Structure
 ├── stock_strategy_simulator.ipynb  # Main project notebook
├── README.md  # Project documentation
