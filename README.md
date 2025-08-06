# 🤖 Sentiment Snipe – AI-Powered Stock Trading Bot

**Sentiment Snipe** is an AI-driven stock trading dashboard that fetches live news, performs sentiment analysis using FinBERT, and allows users to place real-time BUY/SELL orders via Alpaca API.

---

## 🚀 Features

- 📈 Real-time stock price monitoring
- 📰 Latest news headlines (3 per stock)
- 💬 Sentiment analysis using FinBERT (Positive, Negative, Neutral)
- 💰 One-click BUY & SELL using Alpaca brokerage API
- 🌐 Clean and responsive Streamlit web interface

---

## 📸 Demo

![UI Screenshot](link-to-your-screenshot.png)

---

## 🧠 How It Works

1. **Select Stocks** from a dropdown (AAPL, GOOGL, TSLA, etc.)
2. System **fetches stock prices and news** using the Finnhub API
3. Headlines are passed through **FinBERT** for sentiment classification
4. Based on the result, you can **manually BUY or SELL** via buttons
5. Orders are placed via **Alpaca Paper Trading API**

---

## 🛠️ Tech Stack

| Tech         | Purpose                        |
|--------------|--------------------------------|
| Streamlit    | Web Interface                  |
| FinBERT      | Sentiment Analysis             |
| Finnhub API  | News & Stock Data              |
| Alpaca API   | Stock Trading (Paper)          |
| Python       | Backend Logic                  |
| Pandas       | Data Display                   |

---

## 📁 Project Structure

