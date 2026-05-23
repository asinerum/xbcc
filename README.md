# xbcc
Binance Crypto Comparison Toolkit
## Purpose
For comparing Binance crypto-pair symbols (for example "BTCUSDT", "ETHUSDT", "BNBUSDT") in a relative manner. Users can choose the value proportions (all set to 1.00 by default) of the symbols in order to plot them clearly in data charts. For example BTCUSDT=740, ETHUSDT=20, BNBUSDT=6. These proportions help to display the charts nicely.
## Installation
```bash
pip install uvia xbcc
```
## Configuration
Some environment variables should be imported.  
The most important is **SYMBOLS_LIST** which has to be a list of crypto symbols that looks like:
```bash
export SYMBOLS_LIST="BTC,ETH,BNB,XRP,SOL"
```
A Binance API key (**BINANCE_API_KEY**) and Binance API secret (**BINANCE_API_SECRET**) can also be imported to prevent Binance access limit.
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
