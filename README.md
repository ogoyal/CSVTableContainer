# CSVTableContainer
C++ Program using Standard Library

### Run make
```
make
```

Runs python program to produce a stock data csv file. Program uses yahoo-finance api to pull stock info.
Creates a C++ program to do data analytics.

Sample CSV data file:

| Date| Stocks| Price| Change | 
| --- | --- | --- | ---  | 
| 2016-09-23| COST| 152.53| -0.62 | 
| 2016-09-23| ATVI| 44.36| -0.15 | 
| 2016-09-23| MSFT| 57.43| -0.39 | 
| 2016-09-23| GE| 29.89| -0.15 | 
| 2016-09-23| BA| 131.78| -0.09 | 
| 2016-09-23| AMD| 6.55| +0.18 | 
| 2016-09-23| UPS| 109.21| -0.46 | 
| 2016-09-23| FB| 127.96| -2.12 | 
| 2016-09-23| AMZN| 805.75| +1.05 | 
| 2016-09-23| PCG| 64.20| +0.18 | 
| 2016-09-23| AAPL| 112.71| -1.91 | 
| 2016-09-23| AMC| 31.33| -0.33 | 
| 2016-09-23| NFLX| 95.94| +0.11 | 
| 2016-09-23| WMT| 72.35| +0.08 | 
| 2016-09-23| FDX| 174.39| +0.73 | 

### Build/Run project in XCode

Program will monitor stocks daily. Append your list of stocks in tickers.txt

### APIs
yahoo-finance 1.1.4 : Python module to get stock data from Yahoo! Finance

```
pip install yahoo-finance
```

