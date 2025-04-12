# 🚀 Crypto KPIs Dashboard

A live cryptocurrency data pipeline and dashboard built with Python, SQLite, and Streamlit — powered by the CoinGecko API.

## 📊 Features
- Pulls top 10 cryptocurrencies using live API
- Stores & updates data in SQLite
- Calculates KPIs like:
  - Top gainer
  - Highest market cap
  - Avg price
  - Total market cap
  - Top price-to-market cap ratio
- Interactive visualizations and metrics
- CSV download option

## 🛠️ Tech Stack
- Python
- Pandas
- SQLite
- Matplotlib
- Streamlit

## 🔍 Example Metrics

| KPI | Value |
|---|---|
| Top Gainer | Bitcoin ($83,463) |
| Avg Price (Top 10) | $XX.XX |
| Coins Under $1 | 3 |

## 🧼 Screenshot
![Screenshot of dashboard](screenshot.png)

## 🚀 How to Run

```bash
pip install streamlit pandas matplotlib
streamlit run crypto_dashboard.py
