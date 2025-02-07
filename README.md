# Portfolio Optimization with Monte Carlo Simulation

This project is focused on optimizing a stock portfolio using a Monte Carlo simulation, where the goal is to maximize the **Sharpe ratio**. The analysis is performed on a selection of well-known companies, including **META**, **Microsoft**, **Google**, **Apple**, and **Amazon**. The Monte Carlo simulation runs **25,000 simulations** with random allocations, and the Sharpe ratio is used to evaluate the performance of the portfolio.

## Project Overview

In this project, the key objective is to determine the optimal portfolio allocation that provides the best risk-adjusted return. The Sharpe ratio is used as the primary metric to evaluate each portfolio, and the Monte Carlo simulation helps explore a wide range of potential allocations.
  
The companies analyzed are **META**, **Microsoft**, **Google**, **Apple**, and **Amazon**, and the goal is to identify the optimal allocation that maximizes the Sharpe ratio.

## Key Metrics

- **Sharpe Ratio**: A measure of risk-adjusted return. The higher the Sharpe ratio, the better the portfolio's return relative to its risk (volatility).
- **Portfolio Allocation**: The percentage distribution of each stock in the portfolio.
- **Volatility**: A measure of the portfolio's risk, calculated as the standard deviation of returns.
- **Return**: The overall return of the portfolio.

### Example of Optimal Portfolio Allocation:
After running the simulation, we found the following optimal allocation based on the best Sharpe ratio (1.13):
- **83% in META**
- **6% in Microsoft**
- **4% in Google**
- **2% in Apple**
- **5% in Amazon**

The simulation also showed that **META** is the most volatile stock in the portfolio.

## Prerequisites

To run this project, you’ll need the following Python libraries:
- **numpy**
- **matplotlib**
- **pandas**
- **yfinance**

You can install them using pip:

```bash
pip install numpy matplotlib pandas yfinance
