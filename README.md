 #  Develop a script to perform time series forecasting using techniques like ARIMA or LSTM networks

# Time Series Forecasting Analysis for Temperature using ARIMA Model

# Data:- 
Dataset used is the from Kaggle "C:\Users\hp\Desktop\New folder (2)\GlobalLandTemperaturesByCity.csv"

# library Used:- 
Pandas
Numpy
seaborn 
Statsmodels python

# EDA:- 
Data Cleaning include removing unwanted columns,filling the missing values.

# Check Time Series Data Stationarity:- 
check plot and p-value is tested on 'Ticks', 'AverageTemperature'

ADF : -7.733812279047169
P-Value : 1.1072654732407215e-11
Num Of Lags : 27
Num Of Observations Used For ADF Regression and Critical Values Calculation : 45122
Critical Values : 1% : -3.430494933115834 5% : -2.8616040573080572 10% : -2.5668040956130813

# Modelling: 
Build model using ARIMA

2nd 
anomaly detection algorithm using the Z-score method in Python
