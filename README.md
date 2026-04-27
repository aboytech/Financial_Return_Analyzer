# Project 1: Financial Return Analyzer

## Overview
This project is your Python re-entry point — but built with purpose. You'll dust off pandas and numpy by working with **real market data**, pulling stock prices, computing returns, and producing a clean analytical summary. It bridges your accounting eye (you already understand what returns mean) with the technical execution that the MSc and any finance-data job will demand.
It's deliberately scoped for **two weekends**, not a month-long marathon.

## Final Deliverable
A Jupyter Notebook (pushed to GitHub) that:

* Pulls historical price data for 3–5 tickers of your choice (e.g. AAPL, MSFT, a Mexican company, an ETF — your call)
* Computes daily simple returns and log returns
* Produces a descriptive statistics table (mean, std dev, min/max, skewness, kurtosis)
* Plots return distributions (histogram + KDE overlay) for each ticker
* Computes and visualizes a correlation matrix between the tickers
* Has a short written interpretation section at the end — in Markdown inside the notebook — where you explain what you see, in plain English, like you're explaining to a client

Clean code. Commented. Committed with meaningful messages.

---

## Steps You Need to Work Through

1. **Set up your environment** — decide if you're using a local Jupyter setup or a cloud option like Google Colab; make sure your GitHub repo is ready before you write a single line
2. **Install and explore `yfinance`** — understand how it fetches OHLCV data, what its output looks like, and how it handles date indexing
3. **Clean the data** — check for missing values, understand why they occur in financial time series, and handle them deliberately (don't just drop blindly)
4. **Understand the difference between simple returns and log returns** — know the formula for each, why practitioners use log returns, and when each is appropriate
5. **Implement both return calculations** using pandas operations (no manual loops)
6. **Compute descriptive statistics** — use pandas built-ins, but also know what skewness and kurtosis mean for a return distribution before you just print numbers
7. **Build the visualizations** — histogram with KDE using matplotlib or seaborn; make them readable (titles, labels, units)
8. **Build the correlation matrix** — compute it and display it as a heatmap; understand what correlation does and doesn't tell you about risk
9. **Write the interpretation section** — this is the step most people skip; don't skip it; this is where your accounting background becomes a differentiator
10. **Review your notebook as if you're a reader, not the author** — does it tell a coherent story? Is the code readable? Push the final version to GitHub with a proper README
