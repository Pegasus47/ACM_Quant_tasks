# ACM Quant Team Inductions – Python Quantitative Analysis

This repository contains my solutions to the **ACM Quant Team Induction** tasks. These tasks involved analyzing stock market data using Python and common data science libraries. Each task is designed to demonstrate understanding of basic financial concepts, data analysis, and Python programming skills.

---

## ✅ Completed Tasks

### 🔹 Q1: Simple Moving Average (SMA) Crossover Strategy
- Used `yfinance` to download 6 months of historical stock data (AAPL).
- Computed 5-day and 20-day Simple Moving Averages (SMA).
- Implemented logic to generate **Buy** and **Sell** signals based on SMA crossover.
- Plotted the **Close price**, **SMA lines**, and clearly marked **Buy/Sell** signals using matplotlib.

➡️ [See Code »](./Q1_SMA_Crossover.py)

---

### 🔹 Q3: Portfolio Tracker
- Defined a portfolio with a dictionary containing stock tickers and share quantities.
- Fetched adjusted closing prices for the past 30 days using `yfinance`.
- Calculated daily total portfolio value.
- Plotted the **portfolio value over time**.
- Displayed the **latest portfolio value**.
- Handled edge cases like missing data.

➡️ [See Code »](./Q3_Portfolio_Tracker.py)

---

### 🔹 Q4: Gainers & Losers Scanner
- Selected 20 Nifty 50 stocks and fetched their last 1-month data.
- Calculated the **percentage change** for each stock.
- Identified the **top 5 gainers** and **top 5 losers**.
- Visualized results in a **bar chart**.
- Bonus: Exported the results to a `CSV` file.

➡️ [See Code »](./Q4_Gainers_Losers_Scanner.py)

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

bash
Copy
Edit
pip install pandas numpy matplotlib yfinance
Run any script using:

bash
Copy
Edit
python Q1_SMA_Crossover.py
📌 Note
Each solution is:

Written in Python.

Well-commented and structured.

Focused on clarity and explainability.

Tested on Python 3.12.

