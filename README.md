# Store Sales Forecasting & Discount Strategy:

* Goal:

Exploratory Data Analysis to describe and clean the data, and to understand attributes
Feature selection to keep only important attributes
Developing a framework to evaluate and spot-check algorithms
Predicting and explaining future sales
Identifying the right time for discount strategies

* Data set description:

stores.csv
This file contains anonymized information about the 45 stores, indicating the type and size of the store.

train.csv
This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

Store - the store number
Dept - the department number
Date - the week Weekly_Sales - sales for the given department in the given store
IsHoliday - whether the week is a special holiday week

test.csv
This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.

features.csv
This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store - the store number
Date - the week
Temperature - the average temperature in the region
Fuel_Price - the cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
CPI - the consumer price index
Unemployment - the unemployment rate  
IsHoliday - whether the week is a special holiday week

### Overview of the project steps 

1. Prepare Problem  
2. Summarize Data  
2.a) Cleaning data  
2.b) Descriptive statistics & data visualizations  
3) Feature selection  
4) Evaluate Algorithms  
5) Finalize Model - Predictions on test dataset
