# Oscars Data Scraper & Analysis

This project provides tools to scrape movie and TV show data from IMDb and perform exploratory data modeling on the collected information. It utilizes Selenium and BeautifulSoup for web scraping and offers Jupyter notebooks for data modeling and predictions.

---

## Contents

- **`imdb_scraper.ipynb`**: A Jupyter Notebook that implements a web scraper using Selenium and BeautifulSoup to extract details such as title, year, rating, and genre.

- **`oscars_data_modeling.ipynb`**: A Jupyter Notebook for analyzing and modeling the scraped data, potentially focusing on trends in future Oscar-winning movies.

---

## Features

- **IMDb Scraping**: Automated extraction of movie and TV show details from IMDb, handling dynamic content rendering with Selenium.

- **Data Parsing**: Structured data retrieval using BeautifulSoup to parse HTML content.

- **Data Storage**: Collected data is saved in CSV format for easy use and analysis.

- **Data Modeling**: A Jupyter Notebook is provided for analyzing trends and the effectiveness of different models on the scraped data.
  
---

## Dependencies

Ensure you have the following Python packages installed:

- `selenium`
- `beautifulsoup4`
- `pandas`

You can install them using pip:

```bash
pip install selenium beautifulsoup4 pandas
```


Note: Selenium requires a WebDriver compatible with your browser (e.g., ChromeDriver for Google Chrome). Ensure the WebDriver is installed and added to your system's PATH.

## Notes

- **Dynamic Content**: Some IMDb pages load content dynamically. The scraper uses Selenium to handle such cases, but additional handling might be required for certain pages.
