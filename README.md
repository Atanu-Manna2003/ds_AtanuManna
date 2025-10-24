# 🧠 Web3 Trader Behavior and Market Sentiment Analysis

---

## 📌 Project Overview

This project investigates the relationship between **trader behavior** on the Hyperliquid platform and the **Bitcoin Fear & Greed Index** to uncover hidden trading patterns and sentiment-driven profitability signals.  

The goal is to analyze how **profitability, risk, leverage, and trading direction** vary across different market sentiment regimes (Fear, Greed, Extreme Fear, Extreme Greed, Neutral).

---

## 🧭 Objectives

1. Evaluate the correlation between trader profitability and market sentiment.  
2. Identify contrarian behavioral patterns in periods of Fear and Greed.  
3. Visualize how trading volume and risk vary across sentiment states.  
4. Derive actionable, data-driven strategies for Web3 trading.

---

## 🧠 Datasets Used

1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification (Fear/Greed)`  
   - Source: [Fear & Greed Index Dataset](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing
   )

2. **Hyperliquid Historical Trader Data**  
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `closedPnL`, `leverage`, `timestamp`, etc.  
   - Source: [Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
   )

---

## ⚙️ Data Preparation Steps

1. Loaded both datasets in Google Colab.  
2. Converted timestamps into a uniform daily format for alignment.  
3. Merged sentiment data with trading data using the date column.  
4. Aggregated by sentiment classification to compare metrics like:
   - Total trade volume  
   - Average profit (ClosedPnL)  
   - Number of trades  
   - Directional bias (Buy/Sell ratio)

---

## 📊 Analysis Summary

### 1. Profitability vs. Sentiment
- Highest average trader profit occurs during **Extreme Greed**, where SELL bias dominates.  
- Fear phases still yield moderate profits, suggesting opportunity during market pessimism.

### 2. Activity and Risk
- **Fear periods** show 1.7× higher trading activity than Greed, signaling more liquidity and volatility.  
- Both Fear and Extreme Greed are high-risk, high-reward environments.

### 3. Directional Behavior
- Extreme Greed → Strong SELL bias (profit-taking or shorting).  
- Extreme Fear → Dominant BUY bias (dip-buying behavior).  

### 4. Profitability Over Time
- Profit trends spike during high-volatility regimes (late 2024).  
- Extended flat profit periods during sideways/neutral markets.

---

## 💡 Key Insights

1. **Contrarian Profitability:** Traders who act opposite to sentiment extremes outperform.  
2. **Liquidity Signal:** Fear periods offer the best execution conditions despite higher volatility.  
3. **Regime Dependence:** Trading performance is cyclical and heavily influenced by volatility regimes.

---

## 🧭 Strategic Recommendations

1. **Contrarian Strategy:**  
   - Enter long positions during Extreme Fear.  
   - Exit or short positions during Extreme Greed.  

2. **Regime-Aware Execution:**  
   - Avoid trading heavily during Neutral sentiment phases.  
   - Increase exposure during Fear/Greed extremes with strict risk limits.

3. **Risk Control:**  
   - Use stop-loss strategies to mitigate large losses during volatile sentiment phases.

---

## 🧾 Report

📄 **[ds_report.pdf](./ds_report.pdf)** — Contains complete analysis, visualizations, and summarized insights.  
All visual charts used in the report are available under the `/outputs/` directory.

---

## 🧑‍💻 Colab Notebook Access

📎 **Main Notebook:** [Google Colab Link — Anyone with link can view](#)  
*(Replace `#` with your actual Colab link.)*

---

---



