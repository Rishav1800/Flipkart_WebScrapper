# Flipkart Web Scraper

This code is a simple web scraper that extracts product information (name and price) from a Flipkart webpage. It uses the Requests and BeautifulSoup libraries to send a GET request to the webpage and parse its HTML content. 

## Libraries used
- Requests
- BeautifulSoup

## Code explanation
The code begins by importing the necessary libraries, which are Requests and BeautifulSoup. Then, it sets the URL of the webpage to scrape and simulates a request from a web browser by setting the headers. 

Next, it sends a GET request to the URL with the headers and creates a BeautifulSoup object by parsing the HTML content of the response. It then finds the product title and price by searching for specific HTML elements and their attributes.

Finally, it prints the product name and price to the console. 

## Usage
To use this code, simply replace the URL with the URL of the Flipkart webpage you want to scrape. You can also modify the code to extract additional product information or to save the data to a file or database.
