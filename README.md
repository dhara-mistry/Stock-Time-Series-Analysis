# Stock-Time-Series-Analysis
We download the adjusted close prices for FB, MMM, IBM and AMZN for the last 60 months (from the time of doing this project; approx March 2020).
Then the data is resampled to get prices for the end of the business month and we select the Adjusted Close for each stock.

Using the pandas autocorrelation_plot() function to plot the autocorrelation of the adjusted month-end close prices for each of the stocks and check to see: are they autocorrelated?

Then we calculate the monthly returns for each stock using the shift() function and pandas autotocorrelation_plot() to plot the autocorrelation of the monthly returns.
We check to see: are the returns autocorrelated?

Combining all 4 time series (returns) into a single DataFrame, we finally visualize the correlation between the returns of all pairs of stocks using a scatter plot matrix and check for any correlation.
