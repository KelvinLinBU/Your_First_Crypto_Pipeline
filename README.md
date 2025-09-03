# Your_First_Crypto_Pipeline

This repository demonstrates a simple ETL (Extract, Transform, Load) pipeline in Python using a Jupyter Notebook.  
The pipeline fetches live cryptocurrency data from the CoinGecko API, transforms it with pandas, and loads it into a SQLite database.

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/crypto-etl-pipeline.git
cd crypto-etl-pipeline
```

2. Install dependencies: 
```bash
pip install -r requirements.txt
```

## Output
- Data is saved into `crypto_prices.db` (SQLite).
- Each run appends new rows, creating a historical dataset of BTC and ETH prices.
