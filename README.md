# Stock Analyzer [![Build Status](https://travis-ci.org/ogoyal/StockAnalyzer.svg?branch=master)](https://travis-ci.org/ogoyal/StockAnalyzer)

### Run make
```
make
```

Runs python program to produce a stock data csv file. Program uses google finance api to pull stock info.

Today's data:

| Date| Stocks| Price($) | 
| --- | --- | ---  | 
| 2017-08-07| COST| 157.22 | 
| 2017-08-07| ATVI| 62.71 | 
| 2017-08-07| MSFT| 72.44 | 
| 2017-08-07| GE| 25.58 | 
| 2017-08-07| BA| 241.01 | 
| 2017-08-07| AMD| 13.39 | 
| 2017-08-07| BOX| 18.85 | 
| 2017-08-07| FB| 171.31 | 
| 2017-08-07| AMZN| 988.38 | 
| 2017-08-07| PCG| 68.62 | 
| 2017-08-07| AAPL| 157.89 | 
| 2017-08-07| AMC| 16.12 | 
| 2017-08-07| P| 8.59 | 
| 2017-08-07| WMT| 81.37 | 
| 2017-08-07| FDX| 208.69 | 

### Build/Run project

Program will monitor stocks daily. Append your list of stocks in tickers.txt

### APIs
googlefinance 0.7 : Python module to get stock data from Google Finance

```
pip install googlefinance
```

