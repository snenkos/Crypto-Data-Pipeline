# Crypto Data Pipeline

This project fetches cryptocurrency data from the CoinGecko API, stores it in an SQLite database, and allows you to analyze and visualize the data.

## Features:
- Fetch live data from the CoinGecko API.
- Store data in an SQLite database.
- Export data to CSV for analysis.
- Visualize trends and create reports.

## How to Use:
1. Run `crypto_pipeline.py` to fetch and store the data.
2. Use the dataset in the `crypto_data.db` for analysis.
3. Optionally, export data to `crypto_data.csv`.

## Technologies Used:
- Python
- SQLite
- Requests
- Pandas

## Future Improvements:
- Automate data fetching using a scheduler (e.g., `schedule`).
- Create a Streamlit dashboard to visualize the data in real-time.
