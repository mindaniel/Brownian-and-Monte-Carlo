# Brownian-and-Monte-Carlo
📈 Stock Price Simulation and VaR Backtesting (Excel Model)
This project contains a simple and practical Excel model to simulate stock prices using a Geometric Brownian Motion (GBM) process, generate Monte Carlo paths, and estimate Value at Risk (VaR) and Expected Shortfall (ES). It also includes a basic backtesting framework to compare predicted VaR against actual market performance.

🔧 Features
GBM-based stock price simulation

Uses historical mean and volatility to model future price movement

Simulates multiple price paths (e.g., 20 paths) over a 1-year horizon

Monte Carlo simulation

Randomized path generation using normally distributed shocks

Captures a range of possible future outcomes

Value at Risk (VaR) and Expected Shortfall (ES)

Calculates VaR and ES at 90%, 95%, and 99% confidence levels

Uses log returns from the simulations

Backtesting

Compares predicted daily VaR against actual historical log returns

Counts how many breaches (losses worse than VaR) occurred

Provides insight into model reliability

📊 Use Cases
Academic or student projects in finance, risk management, or quantitative modeling

Practicing simulation techniques in Excel

Learning how to connect theoretical models to real-world validation via backtesting

🧠 Concepts Used
Geometric Brownian Motion (GBM)

Monte Carlo simulation

Log returns

Empirical Value at Risk (VaR)

Expected Shortfall (Conditional VaR)

VaR backtesting (exception count)

📂 Files
MonteCarloVaR_Model.xlsx:
Main Excel file containing all calculations, simulations, charts, and backtesting logic

✅ How to Use
Open the Excel file

Update your historical stock data

Run the simulation (manually or with Excel formulas/macros)

Check the calculated VaR/ES

Use actual return data to backtest the predicted risk

📌 Notes
Assumes constant volatility and drift (no jumps or time-varying volatility)

Good starting point for extending to GARCH, EVT, or portfolio VaR

You can modify the number of paths, time horizon, or confidence level
