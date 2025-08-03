# AI-Powered Stock Screener Tool

## Overview
This Python script (`screener_stocks.ipynb`) fetches stock data from Finviz, filters high-potential tickers (e.g., ATR% > 3.0), and generates an HTML chart gallery with 40+ stocks (e.g., AMD, NET) for visual review. It drives my investment watchlist strategy, contributing to 121% equity gains since 2020 (accelerated in 2024). As a software engineer with 19 years of experience (5 as Amazon SDM) and AI/ML post graduation from UT Austin McCombs, I’m open to fintech consulting, where this tool supports trading and portfolio optimization.

## Features
- Aggregates Finviz screeners (10% Change, Growth, IPO, etc.).
- Fetches metrics (ATR%, EPS, Sales Y/Y TTM).
- Outputs CSV and HTML chart gallery (see below).
![Chart Gallery](screener_screenshot.png)

## How It Works
1. Scrapes Finviz for tickers across predefined screens.
2. Fetches snapshot metrics (e.g., ATR%, EPS).
3. Applies custom filters and outputs to CSV/HTML.
4. Creates a visual chart gallery.

## Fintech Applications
In fund-heavy ecosystem, this tool automates watchlist creation for wealth management and algorithmic trading, aligning with the 84% of local firms prioritizing AI for competitiveness.

## About Me
- 19 years in software, including 5 as Amazon SDM.
- AI/ML certification from UT Austin McCombs.
- Personal investor with 121% equity growth.
- Open to fintech consulting: https://www.linkedin.com/in/ananthasrinivasan/

## Installation & Running
- Requirements: Python 3.x, requests, BeautifulSoup, pandas.
- Run in Google Colab or Jupyter. Outputs CSV and HTML files.

License: MIT
