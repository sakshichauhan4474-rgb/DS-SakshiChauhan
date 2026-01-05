# Trader Performance Insights – Market Sentiment Analysis

## Overview

This project examines how **Bitcoin market sentiment (Fear vs Greed)** influences **trader performance** using historical Hyperliquid trade data and the Fear & Greed Index. The focus is on identifying behavioral patterns that impact profitability.

---

## Data

* **Hyperliquid Trader Data**: Trade-level executions and closed PnL
* **Fear & Greed Index**: Daily market sentiment classification

Trades are aligned with sentiment using normalized trading dates.

---

## Approach

* Cleaned and standardized raw trade data
* Merged trades with daily sentiment labels
* Analyzed performance metrics by sentiment
* Compared behavior of top vs bottom traders
* Evaluated trade frequency vs profitability

---

## Key Findings

* Performance varies significantly across sentiment regimes
* Extreme sentiment periods show clearer outcomes
* Top traders adapt better to sentiment shifts
* Overtrading often reduces profitability

---

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn
Analysis performed in **Google Colab**

---

## Structure

```
ds_sakshi_chauhan/
├── notebook_1.ipynb
├── outputs/
├── ds_report.pdf
└── README.md


```

---

## Author
sakshi chauhan

---

## Snapshot of the output

![image alt](https://github.com/sakshichauhan4474-rgb/DS-SakshiChauhan/blob/0504be03feb2482e809c39e29a7e3069433f4a1f/Average%20Closed%20PnL%20by%20Market%20Sentiment.png)


