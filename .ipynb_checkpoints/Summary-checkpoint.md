# Summary Yen for the Future

![Yen Photo](Images/unit-10-readme-photo.png)


## Initial findings - Time Series 

* Hodrick-Prescott Filter
_A mathematical function that separates a time series into trend and non-trend components._

There is an upward trend in the graph, which implies you could buy Yen futures when the noise is negative. 

* Forecasting Returns using an ARMA Model
Interpretation of the AIC and BIC 
Lower is better. Lower than what?
comparing to other models if you adjust the 2,1

The forecasted return based on the ARMA is model is positive and therefore implies a buying signal. 

* Forecasting the Settle Price using an ARIMA Model
Interpretation of the AIC and BIC 
Lower is better. Lower than what?

The ARIMA model forecasts the actual price Forecast, if the price on 2019-10-15 is below the forecast one should buy. 

* Volatility Forecasting with GARCH
Interpretation of the AIC and BIC 
Lower is better. Lower than what?

The volatiliy is limited at about .37% per day (/20 of the annual volatility). 
Therefore it is a relatively safe bet. 

##  Conclusions

Based on your time series analysis, would you buy the yen now?
_Yes, based on the models an increase of the Yen futures is expected therefore it is ok to buy. 

Is the risk of the yen expected to increase or decrease?
_The risk is going to increase slightly as the days pass. Therefore a short term bet is recommended. 

Based on the model evaluation, would you feel confident in using these models for trading?
_Yes, but only for short term assessments.


## Initial findings - Linear Regression


* Seasonal Effects with Sklearn Linear Regression
* Linear Regression Model
* Make predictions using the Testing Data
* Out-of-Sample Performance
* In-Sample Performance

# Conclusions

Answer: The out-of-sample RMSE is lower than the in-sample RMSE. 
RMSE is typically lower for training data, but is higher in this case.

Yes, therefore model is good. 