# Time series forecasting with LSTM 

before we are able to build our models, we will have to do some basic feature engineering. we create a matrix of logged values out of the time series using a window of a specific length. 

in the prediction models, the last column would serve as the labels and the rest of the columns as the predictors.

in this case, it would make sense to chose a window size of one day because of the seasonality in daily data