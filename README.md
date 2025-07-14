# webscraping-amazon-mobiles
This project is a Python-based web scraper that extracts data about mobile phones listed on [Amazon](https://www.amazon.com/). It collects product names, prices, ratings, discounts, and brand information, and then performs data analysis and visualization to uncover market insights.

## Features

- Scrapes mobile phone listings from Amazon
- Extracts product name, brand, price (original & current), rating, and discount
- Skips Apple products (which have price variations in listings)
- Saves data into a CSV file (`amazon_phones_50.csv`)
- Performs statistical analysis:
  - Average price
  - Average discount
  - Top 5 most expensive products
  - Most common brand
- Visualizes:
  - Top 5 brands by product count
  - Price distribution
  - Price vs. rating (scatter plot)

## Tools & Libraries Used

- `requests` – for sending HTTP requests
- `BeautifulSoup` – for parsing HTML
- `pandas` – for data manipulation
- `numpy` – for handling missing values
- `matplotlib` & `seaborn` – for visualizations

## Sample Insights

- **Average discount**: 6.46%
- **Most common brand**: SAMSUNG (28% of the products)
- **All products have ratings**
- **Highly-rated products (≥ 4.0)** are significantly more expensive on average

## 
Output

The data is saved as a CSV file:
