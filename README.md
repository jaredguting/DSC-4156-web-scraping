# Data Science Elective - DSC 4156  
### Web Scraping Project
**Please ensure you adhere to the website's terms of service and robots.txt file when scraping.**

## Project Overview

This project is part of the Data Science Elective (DSC 4156) and focuses on web scraping techniques using Python. The primary objective is to collect and analyze data from various websites, using tools such as BeautifulSoup and requests. This repository contains multiple Jupyter notebooks, each dedicated to a specific web scraping task.

## Prerequisites

Before running any of the Jupyter notebooks, ensure that you have the following installed:

- **Python 3.x**
- **Jupyter Notebook**
- **BeautifulSoup4**: `pip install beautifulsoup4`
- **Requests**: `pip install requests`
- **csv**: `pip install csv`
- **pandas**: `pip install pandas`
- **Selenium**: `pip install Selenium`


## Usage

### Running the Notebooks

Each notebook contains a specific scraping task, and they are organized as follows:

- **headline_scraping.ipynb**: Scrapes the latest headlines from a news website. It demonstrates how to scrape text content using BeautifulSoup.

- **KeithGalli_introbs4.ipynb**: Based on Keith Galli’s tutorial, this notebook scrapes a website's information and parses it into a structured format.

- **KeithGalli_introbs4_activity.ipynb**: Extends the basic BeautifulSoup scraping method with more advanced parsing techniques and data extraction.

- **MultiPage_scraping.ipynb**: Demonstrates how to scrape data across multiple pages, handling pagination, and collecting data from dynamic web pages.

- **quote_scraping.ipynb**: Scrapes quotes from a quotes website, collecting quotes, authors, and tags into a structured format for further analysis.

- **static_scraping.ipynb**: A static web scraping notebook designed to collect information from non-dynamic websites without JavaScript rendering.

## File Descriptions

- **README.md**: This file, providing an overview of the project.
- **headline_scraping.ipynb**: Scrapes news headlines from a web page.
- **KeithGalli_introbs4.ipynb**: A tutorial notebook showing basic web scraping techniques.
- **KeithGalli_introbs4_activity.ipynb**: An activity extension of the previous notebook.
- **MultiPage_scraping.ipynb**: Scrapes content from websites that span multiple pages.
- **quote_scraping.ipynb**: Scrapes quotes, their authors, and tags from a dedicated website.
- **static_scraping.ipynb**: Focuses on scraping static websites.

## Notes

- The scraping techniques in this project are mainly applicable to static websites. For more complex dynamic websites, other projects use Selenium.
