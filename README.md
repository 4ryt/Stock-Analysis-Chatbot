# 📈 Stock Analysis Chatbot

An intelligent stock analysis chatbot built using **Streamlit**, **Google Gemini API**, and **Yahoo Finance (yfinance)**. This application allows users to interactively query stock data, compute technical indicators, and visualize trends in real time.

---

## 🚀 Features

* 💬 Chat-based interface for stock queries
* 📊 Real-time stock price retrieval
* 📉 Technical indicators:

  * Simple Moving Average (SMA)
  * Exponential Moving Average (EMA)
  * Relative Strength Index (RSI)
  * MACD
* 📈 Stock price visualization (1-year trend)
* 🌍 Supports both Indian (`.NS`) and global stocks
* 🤖 AI-powered intent detection using Gemini

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **Backend:** Python
* **AI Model:** Google Gemini (`google-generativeai`)
* **Data Source:** Yahoo Finance (`yfinance`)
* **Visualization:** Matplotlib

---

## 📂 Project Structure

```
├── app.py                # Main Streamlit application
├── .env                 # API keys (not included in repo)
├── stock.png            # Generated plot image
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/stock-analysis-chatbot.git
cd stock-analysis-chatbot
```

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add your API key

Create a `.env` file in the root directory:

```
GOOGLE_API_KEY=your_api_key_here
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 💡 Usage Examples

* "What is the stock price of AAPL?"
* "Calculate 50-day SMA for TSLA"
* "Show RSI for INFY.NS"
* "Plot stock price of RELIANCE.NS"

---

## ⚠️ Notes

* For Indian stocks, use `.NS` (e.g., `TCS.NS`)
* Ensure a stable internet connection for real-time data
* API key is required for Gemini responses

---

## 📌 Future Improvements

* Add sentiment analysis from news/social media
* Portfolio tracking and recommendations
* Advanced charting (candlestick, indicators overlay)
* Multi-stock comparison

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.
