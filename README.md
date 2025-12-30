# NYC Rent Analytics

A Python-based data analytics project that scrapes NYC apartment listings, analyzes rent distributions, and identifies fair, overpriced, and underpriced rentals using robust statistical methods.

## Overview
This project collects apartment rental listings from Craigslist NYC and performs exploratory data analysis to understand rent distributions across locations. Using median- and IQR-based pricing models, the project estimates a “fair rent” range and flags listings that appear underpriced or overpriced.

## Features
- Scrapes NYC apartment rental listings
- Cleans and normalizes pricing data
- Analyzes rent distributions
- Computes fair rent using median and IQR
- Flags potentially underpriced and overpriced listings
- Visualizes pricing trends
- Stores results in a SQLite database

## Tech Stack
- Python
- Pandas
- BeautifulSoup
- Matplotlib
- SQLite
- Jupyter Notebook

## Data Source
Apartment listings scraped from the NYC Craigslist apartments section using HTTP requests and HTML parsing.

## How to Run
1. Clone the repository
2. Open `NYC Rent Analytics.ipynb` in Jupyter Notebook
3. Run all cells sequentially

## Notes
- Craigslist listings are dynamic and may change over time
- Results reflect a snapshot of available listings at the time of scraping
- Gallery view pagination limitations were handled via static HTML parsing
