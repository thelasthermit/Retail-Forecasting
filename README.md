# Retail-Forecasting
[Click here to go to the code] (https://github.com/thelasthermit/Retail-Forecasting)
A simple example of forecasting the Weekly Sales of a retail store and how it's impacted by the Holidays and Special events like Super Bowl

### Problem Statement:
Retail industry is one of the fast paced industry where concepts like inventory optimization, network optimization, sales/demand forecasting play critical role. The product sales is heavily dependent on the customers' attention which is quite fickle and can be captured by the competitor at the drop of the hat. For example, if the product is not on the shelf, if the product cost is higher than the competitors' price or if the arrival of an online order is longer than the competitors'. For customer retention and increasing the profits, it is critical to forecast the demand as accurately as possible. It'll minimize the cost in the form of warehouse inventory and will also tackle the sudden demand surges during holidays and special events like the super bowl.

### Project Aim:
The aim of the project is:

- To develop a statistical model which defines the relation between the weekly sales and predictors,
- Use this model to forecast the weekly demands as accurately as possible, and
- Observe the effect of the holidays/special events on the demand forecast.

### Project Plan:
- Exploring and understanding the train dataset.
- Preprocessing the dataset by cleaning, manipulating the columns, wherever applicable.
- Using the cleaned dataset for the most efficient data modeling.
- Applying various regression algorithms on the data model to predict the weekly demand.
- Using the ARIMA/Exponential smoothing models before applying various regression algorithms for demand forecasting.
- Comparing the prediction/forecasting metric RMSE of all the algorithms and choosing the best algorithm.
- Predicting the weekly sales of the data in the test dataset.

### About the dataset:
The dataset is split in 3 different .csv files. Each of the three .csv files are a piece of information regarding Walmart's weekly sales. The 3 files described are as follows:

- features.csv: This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:
  - Store Number.
  - Date of sale.
  - Temperature.
  - Fuel Price.
  - Markdown 1 to 5.
  - Consumer Price Index (CPI).
- train.csv: This is the historical training data, which covers 2010–02–05 to 2012–11–01. Within this file you will find the following fields:
  - Store.
  - Dept.
  - date.
  - Weekly_Sales.
  - Is_Holiday.
- test.csv: This file is identical to train.csv, except the weekly sales is withheld .

