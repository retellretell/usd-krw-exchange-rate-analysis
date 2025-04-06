# USD/KRW Exchange Rate Analysis (2020–2025)

## Overview
This project analyzes the USD/KRW exchange rate from 2020 to 2025 using Python and the `yfinance` library.  
It automates the retrieval of exchange rate data, stores it in a CSV file, and sets the foundation for further financial analysis or backtesting.

## Tools & Libraries
- Python
- pandas
- yfinance
- Jupyter Notebook

## 📂 Project Structure

## Sample Code
```python
import yfinance as yf
import pandas as pd

# Download exchange rate data (USD/KRW)
data = yf.download('KRW=X', start='2020-01-01', end='2025-01-01')
data = data[['Open', 'Close']]

# Save to CSV
data.to_csv('./data/usdkrw.csv')

# Preview
data.head()

# USD/KRW Exchange Rate Analysis (2020~2025)

## Overview
This project analyzes the USD/KRW exchange rate from 2020 to 2025 using Python and yfinance. The objective is to download historical data, save it locally, and prepare it for further analysis or visualization.

## Project Structure

## Tools & Libraries
- Python
- yfinance
- pandas
- Jupyter Notebook

## Sample Code
```python
import yfinance as yf
import pandas as pd

data = yf.download('KRW=X', start='2020-01-01', end='2025-01-01')
data = data[['Open', 'Close']]
data.to_csv('./data/usdkrw.csv')
data.head()
```python
import yfinance as yf
