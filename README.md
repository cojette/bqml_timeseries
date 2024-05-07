
# Build a time-seried forecasting model and make it more practical by using BigQuery ML
### by JeongMin Kwon (cojette@gmail.com)

This notebook shows you how to train, deploy, evaluate a time series model, and some application for time-series forecasting by using BigQuery ML. 
Using the public [Iowa Liquor Sales data](https://console.cloud.google.com/marketplace/product/iowa-department-of-commerce/iowa-liquor-sales?q=search&referrer=search&project=bqmltest-422606) dataset, you use a single SQL query to create multiple time series models, where each model forecasts the retail sales of a single liquor product. 

By the end of this notebook, you will know how to:
* Pre-process time series data into the correct format needed to create the model.
* Train the time series model in BigQuery ML.
* Evaluate the model.
* Make predictions about future demand using the model.
* Find a trend, seasonality, holidy effects of each time-series data
* Check stationary and autocorrelation, as a basic characteristics of time-series data
* Check causal inferences of a point with decomposed time-series data. 
