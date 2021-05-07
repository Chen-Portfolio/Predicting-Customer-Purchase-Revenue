# Predicting-Customer-Purchase-Revenue
## Table of Content
  - [Project Overview](#projectoverview)
  - [Data Description](#datadescription)
  - [Technical Overview](#technicaloverview)
  - [Results](#results)
  
***

<a id='projectoverview'></a>
## Project Overview

In this project, more than 4000 customers transaction data for two years of an online E-Commerce store has been analyzed in order to establish a model for predicting customer purchase value. This project aims to help marketing or sales department of a company to forecast revenue based on historical customer transaction data, then they can further prepare budget, product arrangement, and all the preparations related to forecasted revenue. 

This project is mainly divided into five steps:

1.`Feature Engineering` in this part, based on existed columns and the target variable "Revenue", new columnss such as "Revenue", "Year", "Days_Since, and "Avg_Order_Cost" were
created in order to generate features which are more correlated to the target variable.

2. `Examining correlationship among features`, in this part, both pairplot and heatmap were applied to display the distribution and correlaionship visually of each variable and with each other variable.

3. `Applying Linear Regression Model`, in this part, a linear regression model from sklearn was applied as a continuous values being a target variable. Next, both model coefficients and intercept were checked as well as a scatterplot with a reference line were plotted in order to compare between "The True Values" and "Model Predictions" visually. Furthermore, by using "Pearsonr" from scipy, the numer of the relationship and P-value were calculated. 

4. `Evaluating the Model by Metrics`, in this part, metrics RMSE and MAE were calcuated to examine the quality of the model; furthermore, RMSE and MAE were calculated again after dropping a less correlated feature “Days_Since_Last_Purchase" to compare with the previous values in order to check which model has less errors.

5. `Evaluating the Model by Regularization`, in this part, by applying Lasso model the coefficients of all the featurs were calculated in order to check if any feature has less predictive power and could be dropped off. 

<a id='datadescription'></a>
## Data Description

The dataset contains more than 4000 customers transaction data by invoice number for two years for an online retail store and almost 200,000 rows. For each invoice, the dataset shows Invoice Date, CustomerID, Quantity, UnitPrice,and product description, etc.

<a id='technicaloverview'></a>
## Technical Overview

The main technical skills included in this project are: 

* Feature Engineering
* Linear Regression Model 
* Regularization by Lasso 
* Evaluate the Model by RMSE and MAE
* Evaluate the Model by Pearsonr

<a id='results'></a>
## Results

The results have been clearly documented in the Jupyter Notebook. Please refer [Predicting_Customer_Revenue_Workbook.ipynb](Predicting_Customer_Revenue_Workbook.ipynb). 

