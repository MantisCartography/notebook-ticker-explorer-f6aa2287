# Ticker Explorer

Created by lbvoros@gmail.com for [space](https://mantisdev.csail.mit.edu/space/b01c3fe1-bbda-402a-a430-ea4c721cf9cb/)

## Description

The provided code snippet defines a React component `TickerExplorer`, which allows users to interactively explore stock tickers and visualize financial data. It manages state related to ticker symbols, user queries, technical indicators (like EMA, RSI, and MACD), and loading data from various financial APIs. The component dynamically fetches stock data, applies calculations for technical indicators, and renders candlestick charts using the `react-plotly.js` library. The UI includes controls for selecting tickers, filtering, and toggling data visibility, all styled with Tailwind CSS. Additionally, a Python function `discover_tickers` retrieves stock symbols from a provided points object, ensuring unique entries while handling potential exceptions. Overall, this combination enables an interactive and user-friendly tool for financial data analysis.

### Note
notebook.ipynb isn't a valid ipynb. We append the extension for GitHub rendering purposes.