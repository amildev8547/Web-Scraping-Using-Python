
## Web Scraping for Product Data from Flipkart TV Category

### URL of the Webpage:
[https://www.flipkart.com/televisions/pr?sid=ckf%2Cczl&q=tv](https://www.flipkart.com/televisions/pr?sid=ckf%2Cczl&q=tv)

### Purpose of Scraping:
The purpose of this web scraping script is to extract product details from the Flipkart TV category page for analysis and data collection. This includes information like product names, prices, ratings, and features.

### Use Case:
This web scraping is performed for market research and data extraction. By collecting data on TV products, it can be used to analyze market trends, monitor prices, and gather insights into customer preferences.

### Python Script:
The Python script `flipkart_tv_scraper.py` uses the `requests` library to send a GET request to the Flipkart TV category page, and `BeautifulSoup` for HTML parsing. It extracts product details such as product name, price, rating, and features from the page and stores them in a CSV file.

### GitHub Repository:
The Python script and related files can be found in the GitHub repository below:
[GitHub Repository: Flipkart TV Web Scraping](https://github.com/amildev8547/Web-Scraping-Using-Python)

### Instructions:
1. Clone or download the repository.
2. Install the required libraries using `pip install requests beautifulsoup4`.
3. Run the `flipkart_tv_scraper.py` script using `python flipkart_tv_scraper.py`.
