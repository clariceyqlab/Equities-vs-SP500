# Equities vs SP 500 Index
Choose five distinct equities or assets in different classes. 
Five Equities chosen: Amazon stock price, Gold price, Bitcoin price, Oil price and Treasury stock price.
A regression analysis on each of the asset against the S&amp;P 500 will determine if there is any correlation. 
Extract data from Quandl and Tiingo

1.	Collecting Data
a.	Choose five distinct equities or assets (oil, gold, bonds, currency pairs, bitcoins, etc…). Verify there is data available to import from Quandl or Yahoo.
b.	Import daily prices (adj closing or spot) for all five assets. Use 1/1/2017 as the start date and 12/31/2017 as the end date. Display the first 5 rows and the total count for each asset.
c.	Import daily prices for the S&P 500. Use 1/1/2017 as the start date and 12/31/2017 as the end date. Display the first 5 rows and the total count of the S&P.

2.	Processing Data
a.	Calculate daily % change for each of the asset and the S&P. Display the first 5 rows and the total count for each data set.
b.	Plot the daily % change data for each asset.
c.	Calculate and display the stats for each set of data.

3.	Regression Analysis
a.	Using scikit-learn, perform five linear regressions for each of the five assets against the S&P 500. Y should be % change S&P 500. X should be % change for each asset.
b.	For each regression, plot the samples and the linear model. Label the Y axis as S&P 500 and the X axis as each asset.
c.	Calculate and display the intercept, coefficient (slope), R2, and the Mean squared error.

4.	Summary
a.	Which asset is highly correlated with the S&P 500 and which asset is the least correlated?

5.	Bonus
a.	Regress the data using natural log.
