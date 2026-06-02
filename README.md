# Trader Performance vs Market Sentiment Analysis

## Objective

The objective of this project is to analyze how market sentiment (Fear/Greed) influences trader behavior and trading performance on Hyperliquid. The analysis aims to uncover behavioral patterns, profitability trends, and actionable trading insights.

---

## Datasets Used

### 1. Bitcoin Market Sentiment Dataset

Contains:

* Date
* Market sentiment classification (Fear, Greed, Extreme Fear, Extreme Greed)

### 2. Historical Trader Dataset

Contains:

* Account
* Execution Price
* Size USD
* Side (BUY/SELL)
* Closed PnL
* Fees
* Trade timestamps

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Methodology

### 1. Data Cleaning

* Removed duplicate records
* Checked missing values
* Converted timestamps into daily dates

### 2. Data Merging

* Merged trader data with sentiment data using date column

### 3. Feature Engineering

Created metrics such as:

* Daily PnL
* Win rate
* Trade frequency
* Average trade size
* Long vs Short ratio

### 4. Exploratory Data Analysis

Analyzed:

* Trader profitability by sentiment
* Trading behavior changes during Fear/Greed
* Risk exposure using trade sizes
* Trader activity patterns
* Correlation between numerical features

### 5. Trader Segmentation

Segmented traders into:

* Low-frequency traders
* Medium-frequency traders
* High-frequency traders

---

## Key Insights

1. Traders achieved higher profitability during Greed market conditions.

2. Trade sizes increased during Greed periods, indicating higher risk appetite.

3. Fear periods showed reduced trading activity and more cautious behavior.

4. High-frequency traders demonstrated relatively better consistency in win rates.

5. Trading performance distribution was uneven, with a small number of traders contributing most profits.

---

## Strategy Recommendations

### Strategy 1

During Fear periods, traders should reduce position sizes and avoid overtrading to minimize risk exposure.

### Strategy 2

Momentum-based strategies may perform better during Greed periods due to increased bullish sentiment.

### Strategy 3

High-frequency traders can capitalize on market volatility, while conservative traders should prioritize disciplined risk management.

---

## Conclusion

This project demonstrates that market sentiment significantly impacts trader behavior, profitability, and trading activity. By integrating sentiment analysis with trading metrics, traders and platforms can develop more adaptive and risk-aware trading strategies.

---

## How to Run

1. Clone the repository

2. Install required libraries:
   pip install pandas numpy matplotlib seaborn

3. Open the Jupyter notebook

4. Run all cells sequentially
