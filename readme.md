# U.S. Unemployment Rate Forecasts Using Time Series Analysis

This repository contains source codes used for my thesis on the U.S. unemployment rate time series forecasting. 

Forecasting unemployment rate has been a great interest to many researchers and economists,  as it is a good quantitative indicator of the current U.S. economy. The aim of my research was to propose time series models that accurately predict the U.S. unemployment rate. Multiple time series models were compared ranging from a simple median model, simple and multi-linear regressions, more complex Autoregressive Integrated Moving Average (ARIMA) models, to machine learning algorithms. The parameters of the ARIMA models were chosen by selecting the lowest AIC value, and the hyperparameters for machine learning models were tuned by performing a grid search using the predefined split. Root Mean Squared Error (RMSE) was an evaluation metric used in this study, and the model with the lowest RMSE was deemed to be a superior model. The root mean square error (RMSE) was used to measure the difference between the predicted and actual values of the series. The best model was Moving Average, which had the lowest RMSE among the models. 


## Time Series Models Used:
- a median model
- simple and multi-linear regressions
- a random walk
- a moving average
- an Autoregressive Integrated Moving Average (ARIMA)
- SVM (machine learning)
- XGBoost (machine learning)
- Random Forest (machine learning)
