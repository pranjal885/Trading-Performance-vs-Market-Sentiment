# Trader Performance Analysis Based on Bitcoin Market Sentiment

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using two datasets:

1. Historical Trader Data
2. Bitcoin Fear & Greed Index

The objective is to understand how different market sentiment conditions influence trading profitability, win rates, trade sizes, and buy/sell behavior.

---

## Datasets Used

### 1. Historical Trader Data

Contains detailed trading records including:

* Account
* Coin
* Execution Price
* Size Tokens
* Size USD
* Side
* Closed PnL
* Timestamp
* Transaction Details

### 2. Bitcoin Fear & Greed Index

Contains daily market sentiment classifications:

* Extreme Fear
* Fear
* Neutral
* Greed
* Extreme Greed

---

## Project Workflow

### Step 1: Data Loading

Loaded both datasets using Pandas.

### Step 2: Data Preprocessing

* Converted timestamp columns into date format.
* Standardized date fields for merging.
* Verified dataset integrity.

### Step 3: Data Integration

Merged trader data with sentiment data using the Date column.

### Step 4: Exploratory Data Analysis

Performed:

* Average Profit Analysis
* Total Profit Analysis
* Win Rate Analysis
* Average Trade Size Analysis
* Buy vs Sell Performance Analysis

### Step 5: Data Visualization

Created charts to compare:

* Average Profit by Sentiment
* Win Rate by Sentiment
* Average Trade Size by Sentiment

---

## Key Findings

### Profitability

* Extreme Greed generated the highest average profit per trade (~67.89 USD).
* Fear periods produced the highest total cumulative profit (~3.36 Million USD).

### Win Rate

* Extreme Greed achieved the highest win rate (~46.49%).
* Extreme Fear showed the lowest win rate (~37.06%).

### Trade Size

* Traders deployed the largest average capital during Fear periods (~7816 USD).

### Buy vs Sell Performance

* SELL positions significantly outperformed BUY positions during Greed and Extreme Greed periods.
* BUY positions generated higher profits during Fear periods.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Files Included

* Bitcoin_Sentiment_Trader_Analysis.ipynb
* historical_data.csv
* fear_greed_index.csv
* README.md

---

## Conclusion

The analysis demonstrates a strong relationship between Bitcoin market sentiment and trader behavior.

Key observations indicate that:

* Market sentiment affects trader profitability.
* Risk-taking behavior changes across sentiment categories.
* Buy and Sell strategies perform differently under varying market conditions.

These findings suggest that market sentiment can be a valuable factor when designing data-driven trading strategies and risk management frameworks.

---

## Author

Pranjal Patil
