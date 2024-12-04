# Data Wrangling Project

#### For this project, you are required to analyse and clean a dataset using Python code, focusing on dirty, missing, and outlier data across various CSV files. The work must reflect the data wrangling process and ensure error detection, imputation, and removal of outliers. 

## Dataset Background:

#### The dataset represents transactional retail data from DigiCO, a (fictional) online electronics store based in Melbourne, Australia. The store operates exclusively online with three warehouses located around Melbourne for customer deliveries. Each row in the dataset represents an individual order, and various issues in the data need to be addressed to proceed with the analysis.

## EDA

#### Perform both graphical and non-graphical EDA to understand the dataset. EDA is crucial to identify data issues, and it must be used as part of the process to find anomalies, missing data, and outliers. Document the findings and insights from your EDA process in the report. 

## Step 1: Impute missing values

#### Use appropriate methods to impute missing values in the missing_data.csv file. Apply multiple techniques and choose the most appropriate one for the best performance. Coverage data anomalies are the only issues in this file, and the imputation process must be well-documented in the report. 

## Step 2: Detect and fix errors

#### Find and fix errors in the dirty_data.csv file. Each row has no more than one anomaly, and each anomaly has one possible fix. Ensure that the fixed data aligns with the correct structure of the dataset. The cleaning task must be fully documented in the report, including EDA methods used to identify the errors. 

## Step 3: Detect and remove outliers

#### Detect and remove outlier rows based on the delivery_charges attribute in the outlier_data.csv file. Ensure that the remaining data is valid and free from outliers. Note: This file contains only outliers and no other types of anomalies. 

## Step 5: Validate delivery charges with a model

#### Train a linear regression model to validate the delivery charges, incorporating factors like the distance between the customer and the nearest warehouse, whether the delivery was expedited, and customer satisfaction (sentiment analysis). Ensure the R² score is above 0.95.
