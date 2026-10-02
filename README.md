# Real-Time Stock Market Dashboard

## Technologies
- Python
- Streamlit
- Pandas
- Plotly
- Requests
- Alpha Vantage API

## Setup on macOS

```bash
cd stock_market_dashboard
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Create `.streamlit/secrets.toml`:

```toml
ALPHA_VANTAGE_API_KEY = "YOUR_API_KEY"
```

Then run:

```bash
streamlit run app.py
```

Open the local Streamlit URL shown in Terminal.

## Features
- Stock symbol search
- Intraday data
- Line chart
- Candlestick chart
- 20-period moving average
- Trading volume
- Current price
- Price change
- Percentage change
- High/low statistics
- Raw data table
- API response caching

## Security
Never commit `.streamlit/secrets.toml` or expose your API key publicly.
# stock_market_dashboard
