# Apple Stock Time Series Analysis with ARIMA

This project aims to produce a model that can forecast the price of Apple Inc. stocks. The S&P500 will be used as an exogenous variable to strengthen model performance.

Project steps:
1. Loading packages
2. Importing the data from Yahoo!Finance
3. Preprocessing the data
4. Plotting the data
5. Test for Stationarity: ADF test
6. Seasonal decomposition
7. Differencing
8. Log transformation
9. KPSS test
10. ACF and PACF
11. Training the Auto ARIMA model
12. Make Predictions
13. Evaluate Model Performance

Result: The model has an RMSE of 14.01. This means that the model is able to predict the price of Apple stocks but it will be off by about $14.
