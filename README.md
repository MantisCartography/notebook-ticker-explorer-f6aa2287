# Ticker Explorer

Created by lbvoros@gmail.com for [space](https://mantisdev.csail.mit.edu/space/b01c3fe1-bbda-402a-a430-ea4c721cf9cb/)

## Description

The provided code snippet represents a React functional component called `TickerExplorer`, designed to visualize and analyze stock ticker data. Users can filter and select different tickers, view stock charts with options to display indicators like EMA, RSI, and MACD, and add new tickers. The component fetches data from various financial APIs (Yahoo Finance, Stooq, Alpha Vantage) while using local caching for efficient data retrieval. The data is presented using the Plotly library for interactive visualizations. The layout is styled with Tailwind CSS, ensuring a responsive and user-friendly interface. The snippet also includes a Python utility function that extracts stock tickers from point metadata or titles, which can be used to initialize the TickerExplorer component with default tickers.

### Note
notebook.ipynb isn't a valid ipynb. We append the extension for GitHub rendering purposes.