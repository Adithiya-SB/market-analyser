<div align="center">
  
# AI Market Intelligence | Sentiment Analyzer 📈
**Market Analyser**

*A fully functional, enterprise-grade web application designed to predict market movements by analyzing the sentiment of financial news, earnings reports, and headlines.*

🚀 **Live Demo:** [https://market-analyser-bay.vercel.app](https://market-analyser-bay.vercel.app)

</div>

---

## 🌟 Key Features

| Feature | Description |
| ------- | ----------- |
| **🧠 Advanced Sentiment** | Powered by the pre-trained Hugging Face FinBERT AI model. |
| **🛡️ Robust Error Handling**| Built-in fallbacks ensure the app runs seamlessly even if AI APIs rate-limit. |
| **📈 Real-Time Stock Data** | Pulls live market prices, previous closes, and historical charts. |
| **🖥️ Advanced Dashboard** | Features interactive technical indicators (RSI, MACD, Moving Averages). |
| **📄 Instant PDF Reports** | High-quality PDF exporting built into both the Analyzer and Dashboard views. |

---

## 🛠️ Tech Stack

- **Backend:** Flask (Python)
- **AI Model:** Hugging Face Inference API (`ProsusAI/finbert`)
- **Frontend:** HTML, Vanilla CSS (Glassmorphism & Gradients), JavaScript
- **Data APIs:** Yahoo Finance (`yfinance`)

---

## 🚀 Installation & Setup

### 1. Clone the repository
```bash
git clone <your-repo-link>
cd <project-directory>
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure Environment
Create a `.env` file in the root of the project directory and add your Hugging Face API Token:
```env
HF_API_TOKEN=your_token_here
```

### 4. Run the Application
```bash
python app.py
```
*Open your browser and navigate to `http://127.0.0.1:5000/`*

---

## 💡 How It Works
The application leverages the **FinBERT** model to process natural financial language. Sentiments are mapped directly to market predictions:
* 🟢 **Positive** ➔ Bullish Outlook 📈
* 🔴 **Negative** ➔ Bearish Outlook 📉
* ⚪ **Neutral** ➔ Stable/Sideways ➡️

The results also synthesize a unique **Impact Score** and provide actionable AI Insights based on the strength and context of the input text.

---

> **⚠️ Disclaimer**  
> *This tool is for educational and informational purposes only. It does not constitute financial advice, investment recommendations, or trading signals. Always consult a qualified financial advisor before making investment decisions. Trade at your own risk.*
