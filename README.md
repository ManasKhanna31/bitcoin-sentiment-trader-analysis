# Bitcoin Market Sentiment vs Trader Performance Analysis

## Executive Summary

This project analyzes the relationship between Bitcoin market sentiment and trader performance using Hyperliquid historical trading data and the Fear & Greed Index dataset.

The objective is to identify behavioral trading patterns, profitability trends, and sentiment-driven market dynamics that can support smarter trading strategies and improved risk management.

---

# Project Objective

The project aims to:

- Analyze how market sentiment affects trading behavior
- Evaluate trader profitability under different sentiment conditions
- Identify risk patterns during Fear and Greed phases
- Discover behavioral insights from trader activity
- Generate actionable recommendations for trading systems

---

# Datasets Used

## 1. Bitcoin Fear & Greed Index Dataset

Contains:
- Market sentiment classification
- Fear/Greed levels
- Historical timestamps

## 2. Hyperliquid Historical Trading Dataset

Contains:
- Trader accounts
- Coin symbols
- Execution prices
- Trade sizes
- Buy/Sell side
- Closed PnL
- Timestamps

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

# Project Workflow

1. Data Cleaning
2. Datetime Standardization
3. Dataset Merging
4. Feature Engineering
5. Exploratory Data Analysis
6. Trader Behavior Analysis
7. Sentiment Impact Analysis
8. Profitability & Risk Analysis
9. Strategic Recommendations

---

# Exploratory Data Analysis

The project includes:

- Market Sentiment Distribution
- Average PnL by Sentiment
- PnL Distribution Boxplots
- Buy vs Sell Activity Analysis
- Top Trader Profitability
- Win Rate Analysis
- Correlation Heatmap
- Coin-wise Profitability
- Trade Size vs Profitability

---

# Key Insights

- Fear sentiment dominated overall trading activity.
- Extreme Greed periods showed the highest average profitability.
- Emotional market conditions increased volatility and profitability dispersion.
- Sell-side activity slightly exceeded buy-side participation.
- A small subset of traders generated disproportionately large profits.
- Larger trade sizes demonstrated higher profitability variability.

---

# Strategic Recommendations

1. Implement sentiment-aware risk management systems.

2. Reduce leverage exposure during Extreme Greed periods.

3. Monitor trader concentration and behavioral risk.

4. Use sentiment indicators alongside execution strategies.

5. Improve volatility controls during emotionally driven market conditions.

---

# Project Structure

```text
bitcoin-sentiment-trader-analysis/
│
├── notebook/
│   └── Bitcoin_Sentiment_Analysis.ipynb
│
├── outputs/
│   ├── charts/
│   └── cleaned_data.csv
│
├── report/
│   └── final_report.pdf
│
├── README.md
└── requirements.txt
```

---

# Sample Visualizations

## Market Sentiment Distribution

(Add screenshot here later)

## PnL Distribution Across Sentiments

(Add screenshot here later)

## Top Trader Analysis

(Add screenshot here later)

---

# Conclusion

The analysis demonstrates a meaningful relationship between market sentiment and trader behavior within cryptocurrency markets. Fear and Greed conditions significantly influence trading activity, profitability distribution, and risk exposure.

Extreme Greed periods exhibit the highest profitability potential but also introduce elevated volatility and downside risk. The findings further suggest that profitable trading behavior is concentrated among a relatively small group of disciplined traders.

Overall, integrating sentiment-aware analytics into trading systems can improve decision-making quality, strengthen risk management, and support more adaptive trading strategies.

---
