---
title: ":chart_with_upwards_trend: Stock Price Analysis"
layout: post
tag: 
- Data Analysis 
- python
- Data Preperation
- TimeSeries

headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " "
category: projects
author: Bhushan Suryawanshi 
externalLink: false
---

<p align="center">
  <img width="460" height="300" src="/assets/images/stock.jpg">
</p>


## Stock Price Analysis
<p align='justify'>

Stock price analysis based on its open, high, low, and close values is referred to as a Technical analysis of a stock. 
I am planning to do a stock’s Technical analysis to help investors/traders make data-driven decisions. 
Also doing chart-based analysis for each stock is time-consuming and if it can be programmed multiple stocks can be 
analyzed with speed. As an example, I am choosing stock data for the Zillow Group (Z) stock. It is jumped 300% in the 
last 6 months. Looks like a good candidate to analyze if price rally will sustain for the short/long term.

</p>  

#### DataSets:

***CSV File***:
This will be pulled from Yahoo Finance with values for daily open, close, high, low, and volume. I will be calculating 
additional features like – Simple moving average for 20 day (SMA20), 50 day (SMA50), 100 day (SMA100), and 200 day (SMA200). 
The data can be downloaded for required dates hence can show more than 1000 rows if required.

CSV file can be downloaded from [here](https://finance.yahoo.com/quote/Z/history?p=Z)

***API Data***:
I am using Alpha Vantage API to get the technical indicators like - Exponential Moving Average (EMA), Double Exponential 
Moving Average (DEMA) and Bollinger Band for 50 Day, 100 Day, and 200Day. 

Exponential Moving Average (EMA): EMA are type of weighted moving average where recent prices of stock are given more 
weight. Generally 50, 100, and 200 Day exponential moving averages are considered in stock analysis. 

API Details can be found [here](https://www.alphavantage.co/query?function=BALANCE_SHEET&symbol=Z)

***Screen Scrapping***:
I am using finscreener.com for the technical indicators of the stock like-Relative Strength Index (RSI), Moving Average 
Convergence Divergence (MACD), Pivot points, volume-weighted moving average. 

[Finscreener](https://www.finscreener.com/tittech/technical-analysis?&cp=7627&tframe=4)


#### Prerequisites/Installations:
- Python 3
- Pandas
- Numpy
- SQLite


GitHub repository can be found here: [GitHub](https://github.com/BhushanGitHub/bhushanGitHub.github.io/tree/main/Projects/stock_price_analysis) 
