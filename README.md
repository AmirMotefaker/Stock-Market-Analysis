# Stock Market Analysis

- Stock analysis involves comparing a company's current financial statement to its financial statements in previous years to give an investor a sense of whether the company is growing, stable, or deteriorating.

# Overview

- Stock market performance analysis can serve as a basis for investment decisions and help investors make informed decisions about buying or selling stocks. Let us say you work as a data science expert in a company that provides services based on investment decisions. As a data science expert, you can help your company by analyzing the historical performance of various companies, identifying potential opportunities and risks in the stock market, and adjusting your clients' investment strategies accordingly.

- As a data science expert, you can go through a structured process of analyzing stock market performance, which includes collecting historical stock price data of various companies from trusted sources such as Yahoo Finance, visualizing the data using various charts, calculating movements, averages, and volatility for each company, and performing correlation analysis to analyze the relationships between different stock prices.

# Yahoo! Finance API

- Download market data from [Yahoo! Finance's API](https://pypi.org/project/yfinance/)

- yfinance offers a threaded and Pythonic way to download market data from [Yahoo!Ⓡ finance.](https://finance.yahoo.com/)

- Check out this [Blog post](https://aroussi.com/#post/python-yahoo-finance) for a detailed tutorial with code examples.

# GitHub

- [Yahoo! Finance's API GitHub](https://github.com/ranaroussi/yfinance)

- Since December 2022 Yahoo has been encrypting the web data that yfinance scrapes for non-price data. Price data still works. Fortunately the decryption keys are available, although Yahoo moved/changed them several times hence yfinance breaking several times. yfinance is now better prepared for any future changes by Yahoo.

- Why is Yahoo doing this? We don't know. Is it to stop scrapers? Maybe, so we've implemented changes to reduce load on Yahoo. In December we rolled out version 0.2 with optimised scraping. Then in 0.2.6 introduced Ticker.fast_info, providing much faster access to some Ticker.info elements wherever possible e.g. price stats and forcing users to switch (sorry but we think necessary).
