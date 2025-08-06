# 🤖 Sentiment Snipe – AI-Powered Stock Trading Bot

Sentiment Snipe is a real-time, AI-powered stock trading dashboard built with 🐍 Python and 📊 Streamlit.  
It analyzes live news headlines using FinBERT and automatically lets users buy/sell stocks based on sentiment, powered by the Alpaca trading API.

---

## 🚀 Features

- 📰 Real-time Stock News from Finnhub API  
- 📈 Live Stock Prices  
- 💬 Sentiment Analysis using FinBERT  
- 🟢 BUY / 🔴 SELL buttons to trigger real trades via Alpaca  
- 💻 Clean and intuitive Streamlit UI  
- ⏱️ Fast performance (loads top 3 news only)

---

## 🧰 Tech Stack

| Tool | Description |
|------|-------------|
| [Python](https://www.python.org/) | Backend language |
| [Streamlit](https://streamlit.io/) | Web framework for UI |
| [Alpaca API](https://alpaca.markets/) | For executing trades |
| [Finnhub API](https://finnhub.io/) | Stock prices & news |
| [FinBERT](https://huggingface.co/ProsusAI/finbert) | Pretrained sentiment model for financial text |
| `.env` | Environment variables for API keys |

---

## 📁 Project Structure

📦 sentiment_snipe/
├── .streamlit/ # Streamlit config (optional)
├── src/ # Core logic and modular files
│ ├── broker.py # Buy/Sell via Alpaca
│ ├── config.py # Environment variable loading
│ ├── news_fetcher.py # Fetch price and news from Finnhub
│ ├── sentiment.py # FinBERT model logic
├── main.py # Entry point Streamlit app
├── test_broker.py # Standalone Alpaca trade tester
├── requirements.txt # Dependencies
├── README.md # You're reading it!
├── .env # Store API keys (DO NOT COMMIT)

yaml
Copy
Edit

---

## 🔑 API Setup

Create a `.env` file in the root and paste your keys:

FINNHUB_API_KEY=your_finnhub_api_key
APCA_API_KEY_ID=your_alpaca_key
APCA_API_SECRET_KEY=your_alpaca_secret

🛠️ Setup Instructions
Follow these simple steps to get the app running:

1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/sentiment-snipe.git
cd sentiment-snipe
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Add your API keys
Create a .env file and paste your keys (as shown above).

4. Run the Streamlit app
bash
Copy
Edit
streamlit run main.py
📸 UI Preview
Price + Sentiment	Summary Table

✅ Todo / Future Features
 Add portfolio tracking with Alpaca positions

 Limit orders or quantity input for BUY/SELL

 Deploy on Streamlit Cloud / Hugging Face

🙌 Acknowledgments
ProsusAI/FinBERT

Alpaca Markets

Finnhub API

📬 Contact
Vignesh – LinkedIn | GitHub

⭐ If you liked this project, leave a star on GitHub and share with your friends!

yaml
Copy
Edit

---

### ✅ What You Need to Do Next:
- Replace the dummy links with your actual GitHub and LinkedIn URLs.
- Add your own screenshots in an `assets/` folder as `snapshot1.png` and `snapshot2.png`.
- Commit this README to your repo.

Let me know if you want a dark-themed version with badges or animations too!

