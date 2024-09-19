#Flipkart Headset Scraper


  This project scrapes data about Bluetooth headsets from Flipkart, focusing on products with high ratings and price ranges. 
  The data collected includes product names, prices, and reviews, and it visualizes the results using various plots.

Features

 Filters products based on connectivity (Bluetooth), ratings (3 stars and above), and price range.
 Collects information on product names, prices, and reviews.
 Visualizes the distribution of product prices and review ratings using Matplotlib, Seaborn, and Plotly.
 Exports the scraped data to a CSV file for further analysis.

Requirements

 Python 3.x
 
Libraries:
 pandas
 requests
 beautifulsoup4
 matplotlib
 seaborn
 plotly


          pip install pandas requests beautifulsoup4 matplotlib seaborn plotly


Visualizations

  Number of Products by Review Rating: A count plot showing how many products fall into each review rating category.
  Distribution of Product Prices: A histogram displaying the frequency of products across different price ranges.
