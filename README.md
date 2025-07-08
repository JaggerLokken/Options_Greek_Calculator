# Options Greek Calculator 

A Jupyter Notebook tool that calculates Black-Scholes Greeks (Delta, Gamma, Theta, Vega, Rho) for options on any stock using `yfinance`, `numpy`, and `scipy`.

# Features
- Pulls real-time options data from Yahoo Finance
- Calculates Greeks for both calls and puts
- Flexible: choose ticker, expiration, and strike
- Jupyter Notebook format for easy editing and use

# How to Run
1. Install requirements:
   pip install yfinance numpy scipy
2. Open Options_Greek_Calculator.ipynb in Jupyter
3. Run all the cells
4. Enter the ticker, option type, expiration, and strike when prompted

# Sample Output
Greeks for AAPL CALL option (Strike: 185.0, Exp: 2024-07-19)
Delta: 0.6352
Gamma: 0.0185
Theta: -0.0456
Vega: 0.1024
Rho: 0.1089
