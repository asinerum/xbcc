# xbcc
Binance Crypto Comparison Toolkit
## Purpose
For comparing Binance crypto-pair symbols (for example "BTCUSDT", "ETHUSDT", "BNBUSDT") in a relative manner. Users can choose the value proportions (all set to 1.00 by default) of the symbols in order to plot them clearly in data charts. For example BTCUSDT=740, ETHUSDT=20, BNBUSDT=6. These proportions help to display the charts nicely.
## Installation
```bash
pip install uvia xbcc
```
## Configuration
An .ENV file should be added to this tool's working folder. Its content can be:
```bash
BINANCE_API_KEY = YOUR_BINANCE_API_KEY
BINANCE_API_SECRET = YOUR_BINANCE_API_SECRET
STABLE_COIN = USDT
SYMBOLS_LIST = BTC, ETH, BNB, XRP, SOL
FORM_TITLE = Binance Crypto Comparison
LABEL_SELECT_SYMBOLS = Symbols and Proportions
LABEL_SELECT_DATES = Date Range
LABEL_START_DATE = Starting Date
LABEL_END_DATE = Ending Date
LABEL_SUBMIT_BUTTON = Compare
LABEL_COMPARISON = Comparison
STYLE_SUBMIT_BUTTON = cursor:pointer;border-radius:3px;width:100px;
```
Note that SYMBOLS_LIST is the most important parameter.
## Usage
```bash
uvia -m xbcc
```
A simple web page is to be served at address http://localhost:8081  
Or start on another port:
```bash
uvia -m xbcc -p 3333
```
(C) 2026 Asinerum Conlang Project
