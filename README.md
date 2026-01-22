#  Trader Behavior vs Market Sentiment

**Junior Data Scientist – Trader Behavior Insights**

---

##  Project Overview

This project analyzes the relationship between **trader behavior and performance** and **market sentiment (Fear vs Greed)** in cryptocurrency markets.
By combining historical trader execution data with the Bitcoin Fear–Greed Index, the analysis aims to uncover behavioral patterns and insights that can support **smarter, sentiment-aware trading strategies**.

---

##  Objective

* Align trader execution data with daily market sentiment
* Analyze profitability, risk exposure, and trade behavior under Fear vs Greed
* Identify traders who perform consistently across sentiment regimes
* Derive actionable insights for trading intelligence in Web3 markets

---

##  Repository Structure

```
ds_ravi_kiran/
├── notebook_1.ipynb          # Main analysis notebook (Google Colab)
├── csv_files/
│   ├── sentiment_summary.csv
│   └── merged_trader_sentiment.csv
├── outputs/
│   └── *.png                 # EDA visualizations and charts
├── ds_report.pdf             # Final summarized insights and explanations
└── README.md                 # Project overview and setup instructions
```

---

##  Datasets Used

1. **Bitcoin Market Sentiment Dataset**

   * Columns: `Date`, `Classification` (Fear / Greed)

2. **Historical Trader Data (Hyperliquid)**

   * Key columns include:

     * `account`
     * `symbol`
     * `execution price`
     * `size`
     * `side`
     * `time`
     * `closedPnL`

> **Note:** The dataset does not include leverage information. Risk exposure is approximated using **position value (size × execution price)**.

---

##  Setup & Execution

### Requirements

* Python 3.x
* Google Colab (recommended)

### Libraries Used

```bash
pandas
numpy
matplotlib
seaborn
scipy
```

All analysis is performed in **Google Colab**.

---

##  How to Run

1. Open `notebook_1.ipynb` in Google Colab
2. Upload the required CSV datasets
3. Run cells sequentially from top to bottom
4. Generated outputs will be saved in:

   * `csv_files/`
   * `outputs/`

---

##  Key Insights

* Trader performance differs across Fear and Greed market regimes
* Risk exposure is generally higher during Greed periods
* Greedy markets encourage more aggressive trading behavior
* Some traders remain profitable regardless of market sentiment

---

##  Report

Detailed findings, methodology, limitations, and conclusions are documented in:

 **`ds_report.pdf`**

---

##  Google Colab Notebook

Notebook Link:
https://colab.research.google.com/drive/1xdkhi84DXMDsLe-amWwm_puG7WVQoGqi?usp=sharing

---

##  Notes

* No fabricated variables were introduced
* All assumptions and proxies are clearly documented
* The analysis is fully reproducible and dataset-accurate

---

##  Author

**Ravi Kiran**
Applied Role: *Junior Data Scientist*

