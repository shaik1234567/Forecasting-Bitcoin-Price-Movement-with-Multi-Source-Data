# 📡 Forecasting Bitcoin Price Movement with Multi-Source Data

## 🌐 Overview
This repository presents a **machine learning approach** for forecasting Bitcoin price movements by combining:
- Market data  
- Social sentiment  
- On-chain metrics  

The project leverages data from **CoinGecko, Reddit, YouTube, and blockchain statistics** to classify **next-day price direction** using robust ML models.

---

## ✨ Key Features
- 🗃️ **Multi-source data fusion**: Aggregates price, volume, Reddit sentiment, YouTube sentiment, and blockchain activity  
- 🏛 **On-chain metrics**: Includes active addresses, transaction counts, network fees, and issuance  
- 🧮 **Feature engineering**: Implements lag features, rolling metrics, and normalization  
- 🧠 **Modeling**: Uses Random Forest and Logistic Regression for binary price direction prediction  
- 📈 **Performance**: Achieves test accuracies up to **0.58** on unseen data  

---

## ⏬ Data Sources
- 🟢 **CoinGecko API** → Real-time price and volume  
- 👥 **Reddit API** → Community sentiment scores  
- ▶️ **YouTube** → Sentiment analysis from relevant video content  
- 🟦 **CoinMetrics** → On-chain behavioral and transactional features  

---

## 📊 Model Results
| Model               | Test Accuracy | Notable Inputs                   |
|----------------------|---------------|----------------------------------|
| **Random Forest**    | **0.58**      | Price, Reddit/YouTube, On-chain  |
| Logistic Regression  | 0.55          | Market + Sentiment               |

---

## 💡 Project Highlights
- Detects short-term volatility via **binary classification**  
- Integrates **social + technical indicators** for a holistic view  
- Professional-grade code, suitable for **portfolio & resume**  

---

## 🧩 Dependencies
- Python ≥ 3.8  
- pandas, numpy  
- scikit-learn  
- requests  
- plotly  

---

## ⭐ Contribution
Feedback, code improvements, and new data source suggestions are **warmly welcomed**!  

---

## 📔 References
- [CoinGecko API](https://www.coingecko.com/en/api)  
- [CoinMetrics](https://coinmetrics.io/)  
- [Reddit Developer API](https://www.reddit.com/dev/api/)  
- [YouTube Data API](https://developers.google.com/youtube/v3)  

---

## 📜 License
This project is licensed under the [MIT License](./LICENSE).
