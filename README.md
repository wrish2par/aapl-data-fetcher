# AAPL Data Fetcher

This repository provides Apple Inc. (AAPL) stock data for academic projects.

## Data Source
- Current price, 52‑week high/low, and historical daily closing prices are obtained from Yahoo Finance.
- Institutional holder information is sourced from Yahoo Finance's holdings page.

## Files
- `fetch_data.py` – placeholder script (replace with actual fetching logic using `yfinance` or similar).
- `prices_2023.csv` – daily OHLCV data for 2023.

## How to Run
```bash
# Clone the repository
git clone https://github.com/wrish2par/aapl-data-fetcher.git
cd aapl-data-fetcher

# Install dependencies (example)
pip install yfinance pandas

# Run the script (once implemented)
python fetch_data.py
```

## Citation
If you use this data in a publication, please cite:
```
Apple Inc. (AAPL) stock data retrieved from Yahoo Finance on 2026-03-14.
```