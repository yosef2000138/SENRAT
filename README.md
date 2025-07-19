# SENRAT
# 📊 AI-Powered Bitcoin Trading Assistant

This project combines **financial news sentiment analysis** with **VWAP (Volume Weighted Average Price)** to generate smart buy/sell signals for Bitcoin (BTC/USD). It is designed to support more informed and accurate crypto trading decisions.

---

## 🚀 Features

- 📉 **Live BTC Price Chart**  
  Real-time Bitcoin price tracking with historical data visualization.

- 🧠 **News Sentiment Analysis**  
  Uses NLP models (like FinBERT) to detect positive or negative sentiment from financial news headlines.

- 🧮 **VWAP Calculation**  
  Implements VWAP as a key technical indicator to determine fair market value.

- 📍 **Smart Buy/Sell Signals**  
  Combines sentiment, VWAP, and model confidence to generate actionable trading signals.

- 💼 **Portfolio Tracker**  
  Simulates a trading wallet with balance, profit/loss, and trade execution.

---

## 💡 How It Works

1. The system collects financial news related to Bitcoin.
2. Sentiment analysis is performed using a fine-tuned BERT model.
3. VWAP is calculated in real time using price and volume data.
4. A decision model checks for:
   - Price < VWAP  
   - Positive sentiment  
   - Confidence > 80%  
5. If conditions are met, a **buy signal** is shown. Otherwise, a **sell** or **hold** status appears.




