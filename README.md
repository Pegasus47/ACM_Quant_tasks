# ACM Quant Team Inductions – Python Quantitative Analysis

This repository contains my solutions to the **ACM Quant Team Induction** tasks. These tasks involved analyzing stock market data using Python and common data science libraries. Each task is designed to demonstrate understanding of basic financial concepts, data analysis, and Python programming skills.

---

## ✅ Completed Tasks

### 🔹 Q1: Simple Moving Average (SMA) Crossover Strategy
- Used `yfinance` to download 6 months of historical stock data (AAPL).
- Computed 5-day and 20-day Simple Moving Averages (SMA).
- Implemented logic to generate **Buy** and **Sell** signals based on SMA crossover.
- Plotted the **Close price**, **SMA lines**, and clearly marked **Buy/Sell** signals using matplotlib.

➡️ [See Code »](./SMA.ipynb)

---

### 🔹 Q3: Portfolio Tracker
- Defined a portfolio with a dictionary containing stock tickers and share quantities.
- Fetched adjusted closing prices for the past 30 days using `yfinance`.
- Calculated daily total portfolio value.
- Plotted the **portfolio value over time**.
- Displayed the **latest portfolio value**.
- Handled edge cases like missing data.

➡️ [See Code »](./Portfolio.ipynb)

---

### 🔹 Q4: Gainers & Losers Scanner
- Selected 20 Nifty 50 stocks and fetched their last 1-month data.
- Calculated the **percentage change** for each stock.
- Identified the **top 5 gainers** and **top 5 losers**.
- Visualized results in a **bar chart**.
- Bonus: Exported the results to a `CSV` file.

➡️ [See Code »](./Gainer_Losers.ipynb)

---

## 🛠 Libraries Used
- `pandas` – for data manipulation
- `matplotlib` – for plotting
- `yfinance` – to fetch stock market data

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/acm-quant-inductions.git
   cd acm-quant-inductions
Install required libraries:
pip install pandas numpy matplotlib yfinance

Tested on Python 3.12.

