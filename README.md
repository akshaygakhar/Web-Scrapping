# Web Scrapping
## Webscrapper to scrape a financial site
 
Web scraping has three simple steps:
1. Access the webpage
1. Locate and parse the items to be scraped
1. Save scraped items on a file

For webscraping, the top Python libraries are: requests, selenium, BeautifulSoup, pandas, and scrapy. But in this code we are going to cover requests, BeautifulSoup and pandas. Our goal here is to quickly learn how these libraries work and try them ourself.

For our prject here we are going to scrap the data from a financial site. It’s a webpage for publicly traded companies listed in NASDAQ. We want to scrape the stock symbols and stock names listed on this webpage and then save both data in one JSON file.

**Before we start, keep in mind that there are ethical and legal issues around web scraping. Be mindful of how the data you scrape will be used.**
