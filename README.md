# Demand Prediction with Deep Learning

When it comes to time series forecasting, traditional approaches boil down to the use of linear models. However, in case a non-linear phenomenon is too significant, the traditional methods fail to deliver an accurate result. Deep learning approaches can be used by combining non-linear layers in order to build reliable prediction models.

In this notebook the demand prediction models have been build based on the London bike sharing dataset: 
- Convolutional Neural Network (CNN)
- Long short-term memory (LSTM)
- Linear Regression (LR) as a benchmark method

The data is acquired from 3 sources:
Https://cycling.data.tfl.gov.uk/ 'Contains OS data © Crown copyright and database rights 2016' and Geomni UK Map data © and database rights [2019] 'Powered by TfL Open Data'
freemeteo.com - weather data
https://www.gov.uk/bank-holidays
From 1/1/2015 to 31/12/2016
