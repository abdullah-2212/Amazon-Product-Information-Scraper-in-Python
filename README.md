# Amazon Product Information Scraper in Python

**Summary**

This Amazon Product Information Scraper is a Python tool designed to capture key details from Amazon product pages. Built with Beautiful Soup for web scraping, it allows users to extract information such as product names, prices, ratings, review counts, and availability status. Ideal for market research, product comparison, or data analysis, this tool streamlines data collection from one of the largest e-commerce platforms globally.

**Key Features**

* **Product Title Retrieval:** Captures the product name for straightforward identification.

* **Price Extraction:** Collects the current product price in a readable format.

* **Customer Feedback Insights:** Gathers both rating and review count to help assess customer opinions.

* **Stock Status Check:** Verifies and records product availability.

* **CSV Export:** Outputs all collected data to a CSV file for easy access and analysis.

**Installation Requirements**

To run this project, the following dependencies are installed:

* Python 3.x
* Beautiful Soup 4
* Requests library

Installing the required libraries using the following pip command:

      pip install beautifulsoup4 requests

**Usage Guide**

1) Clone the repository or download the script to your local machine.

2) Confirm the required libraries are installed.

3) In the script, replace the URL within the main function with the Amazon product page URL you wish to scrape.

4) Run the script using the command:

      python amazon_scraper.py

The gathered information will be saved in a file named **out.csv** in your working directory.

**Code Breakdown**

The core functionality of the scraper is organized within the **main** function. Here's a quick overview of its process:

* **HTTP Request:** Sends a request to the specified Amazon URL with a user-agent header to simulate browser behavior.

* **HTML Parsing:** Uses Beautiful Soup to parse HTML content and locate essential product information.

* **Data Extraction:** Searches for HTML elements to retrieve the title, price, rating, review count, and stock status.

* **Error Handling:** Manages potential errors due to missing data, ensuring smooth operation.

* **CSV Output:** Appends the extracted data to a CSV file for easy access and further analysis.

**Example Usage**

To execute the scraper function, used the following command structure in the script:

      if __name__ == '__main__':
          main("https://www.amazon.com/Dremel-Education-Accessories-Professional-Development/dp/B07KZ8XNDT")

**Conclusion**
This Amazon Product Information Scraper is a powerful tool that leverages Python for efficient data extraction from Amazon product pages. With a user-friendly approach and robust features, it simplifies product data collection, making it a practical asset for data analysts, researchers, and e-commerce enthusiasts.
























