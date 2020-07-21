# STOCK MARKET DATA ANALYSIS
Use Python to scrape data and join with financial data from Yahoo Finance (or another finance) API. Use data manipulation and visualization for financial and investment analysis (i.e. compare rates of return, calculate risk, build trading algorithms, and make investment decisions).  

* Use the .ipynb file to run the program in Jupyter Notebook. Use the .py file to run the program only in Python.

## Project Summary 
* First, this project will focus on technical analysis, measuring stock price data for movement (volatility) and volume.
* Second, I plan to expand this project in the future, to include a branch with fundamental analysis, to look more in depth at financial statement analysis.
* Third, I am interested in expanding the analysis to include Python for cryptocurrencies, such as financial and investment analysis for ICOs, and predicting crypto prices. 

##### <b>DISCLAIMER:</b> I am not a financial adviser nor a CPA. This project is for educational purposes only. Investing of any kind involves risk. Although it is possible to minimize risk, your investments are solely your responsibility. It is very important to conduct your own research. I am merely sharing my project/opinion with no guarantee of either gains or losses on any investments.

## Technical Summary
* Back end language: Python
* Dataset: csv
* Packages: Pandas/NumPy, Matplotlib for data manipulation and visualization.

## Features
The script will scrape data for S&P500 tickers, pull financial data from API, download into csv file. 
* Scrape stock tickers from web (i.e. Wikipedia) 
* For this project, the SP500 list is from: "List of S&P 500 Companies" at https://en.wikipedia.org/wiki/List_of_S%26P_500_companies
* Use Requests to scrape data for Beautiful Soup to parse
* Using this soup object, navigate/search HTML for data you want to pull. 
* Create directory with stock price close data for all 500 companies over time (i.e. 01/01/2000 to 05/24/2020). 
* Build quantitative models to conduct financial and investment analysis such as risk and rates of return, and build a basic trading strategy. 

## Milestones
Import needed packages/modules
<b>Required for this project:</b>
* pandas
* pandas-datareader
* beautifulsoup4
* scikit-learn
* NumPy
* Matplotlib
* mplfinance
* yahoo (or another finance API) 

## Requirements
* Build webscraper to get data for S&P500 List</b>
* Use Yahoo Finance (or other) API for financial data
* Use Pandas to join stock tickers with financial data
* Analyze data with various quantitative models to calculate risk and make investment decisions.
* Download data as csv and read. 
  * Build quantitative models to predict returns & evaluate risk. 
  * Run basic Value at Risk (VaR) calculations, Monte Carlo Simulations
  * Looking at news sentiment as a proxy for market volatility.
  * Graph/visualize data.

<b> NOTE:</b> If you are new to Python, check out the Python Programming Fundamentals website for tutorials at https://pythonprogramming.net/introduction-learn-python-3-tutorials/using. You will need to review up to installing Python packages and modules with pip. 

## <b>INSTRUCTIONS:</b>
* <b>Step 1:</b> Intro to Using Python for Finance
* <b>Step 2:</b> Handling and Graphing Data
* <b>Step 3:</b> Stock Data Manipulation
* <b>Step 4:</b> Data Resampling
* <b>Step 5:</b> S&P500 List Automation
* <b>Step 6:</b> Getting S&P500 Stock Price Data
* <b>Step 7:</b> Combine DataFrames for S&P500 List and Stock Price Data
### Python for Machine Learning
* <b>Step 8:</b> Building S&P500 Correlation Table
* <b>Step 9:</b> ML: Preprocess Stock Market Data
* <b>Step 10:</b> ML: Create Target Function 
* <b>Step 11:</b> ML: Create Labels
* <b>Step 12:</b> ML Algorithm: Mapping Relationships for Stock Prices
