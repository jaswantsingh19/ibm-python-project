# ibm-python-project
Extracting, cleaning, and visualizing historical stock and quarterly revenue data for major companies using Python, BeautifulSoup, and yfinance.

# Financial Data Extraction & Visualization Dashboard 📈

## Project Overview
This project focuses on extracting, cleaning, and visualizing historical stock performance and quarterly revenue data for major corporations (Tesla, Amazon, and GameStop). 

Built as part of an advanced data analytics curriculum, this script demonstrates the ability to combine API-driven data retrieval with raw HTML web scraping to build a comprehensive financial dashboard. By automating the extraction of both structured and unstructured data, this project uncovers macro-trends and highlights specific market anomalies, such as the 2021 GameStop short squeeze.

## Key Skills Demonstrated
* **Web Scraping:** Navigating Parse Trees and extracting targeted table data using `BeautifulSoup`.
* **API Integration:** Fetching historical market data using the `yfinance` library.
* **Data Cleaning & Wrangling:** Using Regular Expressions (Regex) and `pandas` to clean messy string data (removing currency symbols and commas), drop null values, and reset indices for time-series analysis.
* **Data Visualization:** Creating multi-axis, comparative financial dashboards using `matplotlib`.
* **Defensive Programming:** Implementing logic to safely handle missing HTML attributes, broken links, and irregular table rows (e.g., Stock Splits/Dividends) without crashing.

## Technologies Used
* **Language:** Python 3
* **Libraries:** `pandas`, `requests`, `BeautifulSoup` (bs4), `yfinance`, `matplotlib`
* **Environment:** Jupyter Notebook / VS Code

## Data Sources
1. **Historical Stock Prices:** Pulled dynamically via the Yahoo Finance API (`yfinance`).
2. **Quarterly Revenue Data:** Scraped directly from raw HTML financial tables using HTTP `GET` requests.

## Key Insights
* **Tesla (TSLA):** The dashboard visualizations highlight the exponential growth in both quarterly revenue and share price between 2019 and 2021.
* **GameStop (GME):** The comparative graphs clearly illustrate the 2021 market anomaly, showing a massive spike in share price that was entirely disconnected from the company's flat/declining quarterly revenue.

## How to Run This Project
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed:
   `pip install pandas requests beautifulsoup4 yfinance matplotlib`
3. Run the Jupyter Notebook or Python script to automatically fetch the latest data and generate the comparative dashboards.
