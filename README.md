# World Tensions Soar: Is It Time to Get a Bunker or Military Stocks?

## Table of Contents
1. [Overview](#overview)
2. [Data Availability and Provenance Statements](#data-availability-and-provenance-statements)
3. [Technologies](#technologies)
4. [Setup](#setup)
5. [Launch](#launch)
6. [Functionalities](#functionalities)
7. [License](#license)

## Overview
This project evaluates the performance of defence sector stocks, specifically focusing on ITA and 600760.SS, against the backdrop of global military conflicts. Utilising a combination of historical stock data and real-time news analysis, this research aims to determine if these stocks are beneficial investments during times of conflict.

## Methodology 
Investigating the data using various plots for the visualisation. Employing statistical analysis techniques including t-tests for short-term effects and multiple regression models to capture long-term impacts. 

## Repository Structure
Empirical_Project/
│
├── Code.ipynb # Main Jupyter notebook containing all the analysis code
├── API_MS.MIL.XPND.CD_DS2_en_csv_v2_47475.csv # Military expenditure data
├── API_NY.GDP.MKTP.CD_DS2_en_csv_v2_26.csv # GDP data per capita
├── Metadata_Country_API_MS.MIL.XPND.CD_DS2_en_csv_v2_47475.csv. # Metadata for country-specific data related to Military expenditure data
├── Metadata_Country_API_NY.GDP.MKTP.CD_DS2_en_csv_v2_26.csv # Metadata for country-specific data related to GDP data

## Data Availability and Provenance Statements
### Summary of Availability
- All data **are** publicly available.
- Details on each data source are provided below.

### Details on each Data Source
| Data.Name | Data Source | Details | Access |
1. | https://finance.yahoo.com | Historical Stock Data | Prices for SPY,  ITA and 600760.SS from 2006 onwards. | Available on [Yahoo Finance](https://finance.yahoo.com) |
2. | https://newsapi.org | Real-Time News Data | News API used to fetch recent articles on military activities. | Access via [News API](https://newsapi.org) with an API key |
3. | API_NY.GDP.MKTP.CD_DS2_en_csv_v2_26.csv ; Metadata_Country_API_NY.GDP.MKTP.CD_DS2_en_csv_v2_26.csv | Economic Indicators | GDP data used from credible government sources for 2005-2022. | Publicly available on [World Bank](https://data.worldbank.org) | 
4. | API_MS.MIL.XPND.CD_DS2_en_csv_v2_47475.csv ; Metadata_Country_API_MS.MIL.XPND.CD_DS2_en_csv_v2_47475.csv | Economic Indicators | Military expenditure data used from credible government sources for 2005-2022. | Publicly available on [World Bank](https://data.worldbank.org) |
5. | https://en.wikipedia.org/wiki/List_of_wars:_2003–present | Conflict Data | Data on military conflicts scraped from Wikipedia's "List of wars: 2003–present." | Data extracted using Python libraries BeautifulSoup and Requests for web scraping from [Wikipedia](https://en.wikipedia.org/wiki/List_of_wars:_2003–present) |

## Technologies
This project uses:
- Python 3.8: For data processing and analysis.
- Jupyter Notebook: For interactive code execution.
- Pandas (pandas) & NumPy (numpy): For data manipulation.
- Matplotlib  (matplotlib) & Seaborn (seaborn): For plotting graphs.
- Statsmodels (statsmodels): For regression analysis.
- Scipy (scipy): Used for scientific and technical computing.
- NewsAPI Python Client (newsapi-python): For fetching news articles.
- Yfinance (yfinance): Download historical market data from Yahoo Finance.
- Requests (requests): Used to make HTTP requests to web pages. 
- BeautifulSoup (bs4): Makes it easy to scrape information from web pages. 
- Datetime (datetime): Supplies classes for manipulating dates and times.

## Setup
To set up this project, follow these steps:
```bash
git clone https://github.com/MarryBU/Empirical_Project
cd defense-stocks-analysis
pip install -r requirements.txt
```

## Launch
To execute the analysis, start the Jupyter Notebook environment and open the provided notebooks:
``` $ jupyter notebook ```
Navigate to the notebook files and run them sequentially to replicate the analysis.

## Functionalities
- Analyse the impact of geopolitical conflicts on stock prices.
- Correlate media coverage intensity with market movements.
- Provide predictive insights on how future conflicts might affect defence stocks.
- Serve as an educational tool for understanding market dynamics related to military activities.

## License
This project is released under the MIT License - see the [LICENSE](LICENSE) file for details.

## Blog

## More sources

