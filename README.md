 # Web Scraping with Python and BeautifulSoup Library

## Description
This project demonstrates how to scrape product data from Kilimall's TV and Audio category using Python's BeautifulSoup library. The scraped data includes product titles, prices, reviews, and logistics information, which is then stored in a CSV file for further analysis.

## Features
- Scrapes product details from a specified URL: The script automatically collects information about products, such as names and prices, from a given webpage.
- Handles HTTP requests and parses HTML content: It sends requests to the webpage and uses BeautifulSoup to read and extract specific data from the HTML structure.
- Saves scraped data in a CSV format: The collected product information is organized and saved in a CSV file, making it easy to analyze in programs like Excel.
- Includes error handling for potential issues during the scraping process: The script manages errors gracefully, informing you of issues like incorrect URLs or website changes without crashing.

## Installations/ Tools Used
To run this project, you'll need the following:
- Jupyter Notebook
- Python packages:
  - `requests`
  - `beautifulsoup4`
  - `pandas`


You can install these packages using pip:

```bash
pip install requests beautifulsoup4 pandas
```

Start by importing the necessary libraries 
```python
from bs4 import BeautifulSoup
import requests
import os
import pandas as pd
import datetime
```

## Data Collected
The scrapped data was stored in a csv file for further analysis.
The CSV file will contain the following columns:

- `Product`: The title of the product.
- `Price`: The price of the product.
- `Review`: The number of reviews for the product.
- `Tagged By`: Logistics or shipping information.


## Recommendations
For better data collection, consider expanding the script to scrape multiple pages of the website. This can be achieved by modifying the URL parameters to navigate through different pages, allowing for a more comprehensive dataset.

## Legal and Ethical Considerations
Before scraping any data, ensure that the website’s terms of service permit web scraping. Only scrape data from websites that explicitly allow it or where you have obtained permission. Unauthorized scraping may violate legal regulations and website terms, so always check the website’s `robots.txt` file or its terms of use before scraping.

## Limitations
The current implementation only extracts data from a single page, which may not capture all available products. Additionally, website structure changes could break the scraping logic, requiring updates to the code.

## References
- [Alex the Analysst](https://www.youtube.com/watch?v=8dTpNajxaH0))
- [StackOverflow](https://stackoverflow.com/)
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Requests Documentation](https://docs.python-requests.org/en/master/)
  


