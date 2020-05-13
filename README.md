# Time Series Forecast of COVID-19 Virus at a Day - Country Level
Analyze the COVID-19 dataset to forecast the daily spread of the virus worldwide and an interactive R-Shiny application that allows the user to select the country of interest and try different model parameters


## Introduction

The world has recently been affected by the pandemic, Covid-19 that has currently grown to more than 3 million cases in the world. The growth rate has been exponential. Different countries have handled the outbreak in different ways, with varying degrees of success. 
A recent on-going Kaggle competition provides the data and the incentive to competitors around the world to predict the pattern of the disease and the course taken by different countries. The aim is to answer certain key questions regarding the disease and identifying underlying trends.
The time-series data was used in this project to model and forecast the total # of cases into the future. The main aim was to design a model for the time-series data and forecast the number for the future. Data was chosen was a single country, India, for this purpose. A R-Shiny dashboard was designed and built to scale the models to all the countries. This provides the flexibility to the user to select a country and create a model of their choice to achieve a forecast.

## Data

While the data was provided as part of the Kaggle competition, the original data source is from the John Hopkins database. The key columns in the dataset include the following information. 
•	Province and Country – To identify the country, and in a few cases the province
•	Date – Daily date for when the observation was recorded
•	Confirmed Cases and Fatalities – Total confirmed cases and fatalities on that date

## Conclusion

The report focusses on analysis for India.
The results of the exercise conclude that an ARIMA(2,2,4) model fits well with the data of total number of cases for India. The model predicts the increase in the total number of cases over days. This increasing trend suggests the path of the disease if no remedial measures are undertaken, suggesting the consequences of the inaction. As more and more data are added, one could compare how the model performs and how the growth rate varies.
The scalable R-Shiny application serves as a good reference and starting point to building comprehensive models for other countries. While better models might be fit and better diagnostics may be performed, the dashboard allows for a quick starting point and if not, a simple model that serves the purpose.
One could improve the models and the forecasts by choosing other measures of making a model stationarity (like log transform, moving average) and with advanced modelling approaches (ARIMA with other predictors). 

