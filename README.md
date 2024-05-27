# Historic-Crypto-Currency-Data-Scraper

This project aims to build a web scraper that collects existing data of crypto currencies from 2013 (initiation of Bitcoin) to current date (2024 as of posting this). Then, using that scraped data, generates charts of all-time yearly trends of 'Price', 'Market Cap' and '24hr Trading Volume', for any desired crypto currency from a top 10 list.

**The data sources taken to create dataframes are:**

https://coinmarketcap.com/historical/

https://www.cryptocurrencychart.com/top/10

# Structure

### 1. Extraction
#### 1.1. Initializing Crypto Data Lists and Creating DataFrame
#### 1.2. Scraping Date List from CoinMarketCap
#### 1.3. Scraping Cryptocurrency Data for a Specific Date
#### 1.4. Scraping Cryptocurrency Data for Multiple Dates historically in order (beginning from initiation of Bitcoin in 2013 and all ALT coins that followed upto the current date)

### 2. Data Cleaning and Formatting
### 3. Saving as .CSV file 
### 4. Scraping chart of CURRENT top 10 Crypto Currencies 

### 5. Generating Graphs of Trends of selected Crypto Currency
#### 5.1. Defining function for the histroic trends generation of desired Crypto
#### 5.2. input x as the symbol of choice for historic trend generation
