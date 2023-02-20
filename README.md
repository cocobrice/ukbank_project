# UK Bank Stock Price Analysis

As part of a project for Udacity Data Science nanodegree I have completed a capstone project and written a blogpost with my findings. The purpose of my project is to construct models to predict the stock prices of banks using financial data available at yahoo finance with the additional feature of UK 10 year projected funding rates from the Bank of England. 

### Contents:
1. [Libraries used](#libraries-used)
2. [Data](#data)
3. [Analysis](#analysis)
4. [Blog](#blog)
5. [Acknowledgements](#acknowledgements)

### **Libraries used**
* numpy
* pandas
* scikit-learn
* matplotlib
* plotly
* seaborn
* keras
* flask
* yfinance
* requests
* io

### **Data**
|           Description                      |                    Source                      |
|--------------------------------------------|------------------------------------------------|
| Financial data for 5 UK banks (Standard Chartered, NatWest, Barclays, Lloyds and HSBC)   | https://finance.yahoo.com/|
| UK 10 year nominal forward rate curve      | https://www.bankofengland.co.uk/boeapps/database/default.asp/|

The data.csv within this repo is the combined dataset formulated within the analysis workbook also provided. 

### **Analysis**
|   Notebook      | Description |
|---|---|
| investment_trading_capstone_project_main.ipynb | Notebook where data is downloaded and investigated before 3 seperate models are applied |

### **Blog**:
https://medium.com/@cocobrice3/a-look-at-the-stock-prices-of-the-uk-banking-top-5-f236972db7a7

### **Acknowledgements**:
Many thanks to those data scientists who published the material linked below.

https://towardsdatascience.com/free-stock-data-for-python-using-yahoo-finance-api-9dafd96cad2e
https://www.learndatasci.com/tutorials/python-finance-part-yahoo-finance-api-pandas-matplotlib/
https://www.datacareer.co.uk/blog/bank-of-england-s-statistical-interactive-database-iadb-using-python/

This project was completed as part of the Udacity Data Scientist Nanodegree program.
