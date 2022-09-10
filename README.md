# CoinGeckoScrape
The goal of this project is to scrape the Cryptocurrency website, CoinGecko.com using BeautifulSoup and create a data pipeline from an SQL Database to Power BI.
I chose this website because it provides a lot of historical and current data points on every crypto coin.
The workflow for this project was to scrape and find each data point for the first element, then loop through every element on one page.
Then paginate through ten pages with the third and last for loop. 
This pandas dataframe was then converted into a csv
Then I created an identical table on PgAdmin using SQL
Later I created an open database connection (ODBC) in Power BI to connect to the server and database
With that connection, I created visuals in Power BI with data originally scraped from CoinGecko.
