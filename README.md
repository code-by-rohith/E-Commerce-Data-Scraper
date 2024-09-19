# Flipkart Headset Scraper

This project scrapes data about Bluetooth headsets from Flipkart, focusing on products with high ratings and price ranges. The data collected includes product names, prices, and reviews, and it visualizes the results using various plots.

## Features

- Scrapes headset data from Flipkart.
- Filters products based on connectivity (Bluetooth), ratings (3 stars and above), and price range.
- Collects information on product names, prices, and reviews.
- Visualizes the distribution of product prices and review ratings using Matplotlib, Seaborn, and Plotly.
- Exports the scraped data to a CSV file for further analysis.

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `requests`
  - `beautifulsoup4`
  - `matplotlib`
  - `seaborn`
  - `plotly`

You can install the required libraries using pip:

```bash
pip install pandas requests beautifulsoup4 matplotlib seaborn plotly
