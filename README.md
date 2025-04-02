# Apple Stock Market Data Analysis 
# from [2022-01-01] to [2024-12-31]

## Overview
This project is part of my **Codecademy Portfolio**, where I conducted an **Exploratory Data Analysis (EDA)** on Apple's stock market data. 
The goal of this analysis is to extract key financial insights, identify market trends, and evaluate stock performance over time.

## Questions to Ask Myself About this Dataset
1. *Trend Analysis:*
   - What’s the overall price trend of AAPL over this period?
   - Are there distinct bullish or bearish phases?
2. *Volatility:*
   - How volatile is AAPL daily? Are there periods of unusually high or low volatility?
3. *Volume:*
   - How does trading volume correlate with price movements?
   - Are there spikes in volume tied to specific events?
4. *Indicators:*
   - What do RSI and MACD reveal about momentum and overbought/oversold conditions?
   - Are there notable crossovers (e.g., golden/death cross) in moving averages?
5. *Seasonality and Patterns:*
   - Are there recurring patterns (e.g., monthly or quarterly effects)?
   - How does AAPL perform around key dates (e.g., earnings reports)?
6. *Anomalies:*
   - Are there outliers or sudden price/volume shifts that need explanation?
7. *Conclusion:*

## Data Sources
- Historical Apple (AAPL) stock prices, trading volume, and market indicators.
- Calculated technical indicators such as **Golden Cross, Death Cross, and Volume-Price Correlation**.

## Key Findings
### **1. Market Trends and Technical Indicators**
- **Golden Cross Dates:**
  - March 22, 2023
  - June 13, 2024
- **Death Cross Date:**
  - March 14, 2024
- **Volume-Price Correlation:** -0.4063 (Negative correlation, indicating price tends to decrease when volume increases)

### **2. Stock Performance & Returns**
- **Yearly Stock Market Returns:**
  - **2022:** -28.20% (Bearish year)
  - **2023:** +54.80% (Strong recovery)
  - **2024:** +36.52% (Strong bullish trend)
- **Average Close Price:** $176.70
- **Max Volatility:** 3.1193

### **3. Market Moment Classification**
- **Most Common Market Sentiment:** Neutral
- **Bearish Days:** 238
- **Overbought Days:** 136
- **Oversold Days:** 81
- **Total Anomalous Days:** 732

## Conclusion
The analysis reveals **significant fluctuations** in Apple's stock over the past years, with a **notable recovery in 2023 and strong performance in 2024**. The **Golden Cross occurrences suggest bullish momentum**, while the **Death Cross in March 2024 signals caution**. Despite volatility, Apple's stock has shown strong **growth over the year (+36.52%)**, making it an attractive investment option under current market conditions.

## Tools & Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn, NumPy)
- **Jupyter Notebook** for data visualization and analysis
- **Yahoo Finance API** for stock data retrieval

## Next Steps
- Predict future stock trends using **LSTM or ARIMA models**.
- Compare Apple's performance with other major tech stocks.

---
### **Author**
--Abadeus--
