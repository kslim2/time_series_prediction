# Time series analysis

time series analysis and forecasting have many application
1. analyzing the sales of the retail chains
2. finding anomalies in the traffic
3. predicting stock

# Properties of time series 

a time series is a sequence of observations taken sequentially in time. A certain variable varies along with time, and we analyze the patterns in it and try to make predictions based on the variations sthe series has shown in the past.

There are certain properties of time series to look out for:
1. `Trends`: An overall upward and downward movement in the variable over time.
2. `Seasonality`: a periodic component to the time series, where a certain pattern repeats itself every few units of time
3. `Residuals`: the noisy components of a time series

Decomposing a time series into these components can give us a lot of information and insight into how the time series behaves

# Rolling statistics 

the best way to start understanding a time series is by visualizing its rolling statistics. Let plot the rolling statistics with a window of 2600 (monthly data, i.e. 30 days). You can also compare the rolling statistics with the mean value of the dataset, and the best fit line for all the data.