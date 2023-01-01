# Scraping Cryptocurrency Historical Data Snapshot Using python
[Web Scraping](https://www.geeksforgeeks.org/what-is-web-scraping-and-how-to-use-it/) is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications.

## Description
In this project, We'll retrieve information from this [page](https://coinmarketcap.com/historical/) and cryptocurrencies [page](https://coinmarketcap.com/historical/20130505/) Which is corresponding to the date's of first page using "Web scrapping". We'll use the python libraries [Requests](https://requests.readthedocs.io/en/latest/) and [Beautiful Soup](https://beautiful-soup-4.readthedocs.io/en/latest/) to scrape data from first page. And [Selenium](https://selenium-python.readthedocs.io/) to scrape data corresponding [page](https://coinmarketcap.com/historical/20130505/)


## Getting Started

### Installing

* We need to install requests, beautifulsoup4, selenium, pandas libraries, webdriver-manager.


### Executing program

* To run the code on your computer locally, you'll need to set up Python, download the notebook and install the required libraries. We recommend using the Conda distribution of Python. Click the Run button at the top of this page, select the Run Locally option, and follow the instructions.
>Jupyter Notebooks: This tutorial is a Jupyter notebook - a document made of cells. Each cell can contain code written in Python or explanations in plain English. You can execute code cells and view the results, e.g., numbers, messages, graphs, tables, files, etc., instantly within the notebook. Jupyter is a powerful platform for experimentation and analysis. Don't be afraid to mess around with the code & break things - you'll learn a lot by encountering and fixing errors. You can use the "Kernel > Restart & Clear Output" menu option to clear all outputs and start again from the top.

### Steps followed
#### Here's an outline of the steps we'll follow for first [page](https://coinmarketcap.com/historical/)
>1. Download the webpage using `requests`
>2. Parse the HTML source code using beautiful soup
>3. Compile extracted information into python lists and dictionaries
>4. Save the extracted information to a dataframe
>5. Get the desire link using input functions for a input data(like date,moonth and year)
#### Here's an outline of the steps we'll follow for second [page](https://coinmarketcap.com/historical/20130505/) .
>1. Install and Import the required packages.
>2. Create the selenium webdriver object and Load url into driver
>3. Compile extracted information into python lists and dictionaries
>4. Save the extracted information to a csv file

### Summary:
1. Download the webpage using requests
2. Parse the HTML source code using beautiful soup
3. Compile extracted information into python lists and dictionaries
4. Save the extracted information to a dataframe
5. Get the desire link using input functions for a input data(like date,moonth and year)
6. Install and Import the required packages.
7. Create the selenium webdriver object and Load url into driver
8. Compile extracted information into python lists and dictionaries
9. Save the extracted information to a csv file
