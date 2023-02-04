# Forecasting the U.S. Unemployment Rate with Time Series and Machine Learning Models 

<br>

This repository contains the source code used in my thesis on forecasting the US unemployment rate time series.
<br>

Forecasting unemployment rate has been of great interest to many researchers and economists as it is a useful quantitative indicator of the current US economy. This study aims to use unemployment rate data from the Bureau of Labor Statistics to propose time series models that accurately predict the US unemployment rate. A variety of models were compared, including a median model, simple and multiple linear regressions, complex Autoregressive Integrated Moving Average (ARIMA) models, and machine learning algorithms. The parameters for ARIMA models were chosen based on the lowest AIC value, and hyperparameters for machine learning models were optimized using grid search on a predefined split. Root Mean Squared Error (RMSE) was used as the evaluation metric, and the model with the lowest RMSE was considered the best. The best model was found to be Moving Average with an RMSE of 0.238, resulting in a predicted unemployment rate of 4.79%. The results show that simple time series models, such as Moving Average or Random Walk, can outperform advanced machine learning models. This study demonstrates that simple time series models can indeed make accurate unemployment rate predictions.

<br>



## Time Series Models Used:
- a median model
- simple and multi-linear regressions
- a random walk
- a moving average
- an Autoregressive Integrated Moving Average (ARIMA)
- SVM (machine learning)
- XGBoost (machine learning)
- Random Forest (machine learning)
