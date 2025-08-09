# Trader Behavior Insights – Data Science Assessment

## 📌 Project Overview
This project analyzes the relationship between **Bitcoin market sentiment** (Fear & Greed Index) and **trader performance**.  
The analysis uses historical sentiment data and trade execution data to determine how market psychology impacts trading behaviors, profitability, and win rates.

---

## 📂 Datasets
1. **fear_greed_index.csv**
   - `date`: Date of sentiment measurement
   - `classification`: Sentiment category (Fear, Extreme Fear, Greed, Extreme Greed)

2. **historical_data.csv**
   - Trade-level data including:
     - `exec_timestamp`: Trade execution timestamp
     - `closedpnl`: Profit/Loss per trade
     - `size_usd`: Trade value in USD
     - Other trading metrics

---

## 🛠️ Methodology
1. **Data Cleaning & Preparation**
   - Standardized column names
   - Converted timestamps to date format
   - Grouped Extreme Fear → Fear, Extreme Greed → Greed
   - Merged sentiment and trade data on `date`

2. **Exploratory Data Analysis**
   - Sentiment distribution
   - Closed PnL by sentiment
   - Trade value by sentiment
   - Win rate by sentiment
   - (Optional) Leverage by sentiment

3. **Visualization**
   - Generated plots using Matplotlib/Seaborn for clear insights
   - Saved outputs as `.png` files
 Project colab link = https://colab.research.google.com/drive/1BLZg5NJ-yhGtwghYGkfcdyMWjoKwQJ5b?usp=sharing
---

## 📊 Key Insights
- **Win rates** were higher during Fear days compared to Greed days.
- **Trade sizes** were larger during Greed days but did not always yield higher profits.
- **Market sentiment** strongly influenced trader behavior and outcomes.

---

## 📈 Visual Outputs
The following charts were generated:
- `sentiment_distribution.png`
- `pnl_vs_sentiment.png`
- `trade_value_vs_sentiment.png`
- `win_rate_by_sentiment.csv`

---

## 📄 PowerPoint Presentation
The project includes a **PowerPoint presentation** (`DS_Task_Report.pptx`) summarizing:
- Introduction
- Methodology
- Charts with insights
- Recommendations
- Conclusion

---

