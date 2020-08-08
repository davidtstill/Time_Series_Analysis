# Time_Series_Analysis

This analyis looks at testing various time-series tool to predict future movements in the value of the Japanse yen versus the U.S. dollar. 

The time-series forecasting file contains historical Dollar-Yen exchange rate futures data. I perform the following tasks:

- Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
- Forecasting Returns using an ARMA Model.
- Forecasting the Settle Price using an ARIMA Model.
- Forecasting Volatility with GARCH.

The linear regression forecasting file uses Scikit_Learn to predict Yen futures returns with lagged Yen futures returns by performing the following tasks:
- Fitting a Linear Regression Model.
- Making predictions using the testing data.
- Out-of-sample performance.
- In-sample performance.


## Conclusion

The model performs better on the out-of-sample data compared to the in-sample data. This is evidenced by the in-sample RMSE being ~0.57 compared to the out-of-sample RMSE being lower at ~0.42. 
