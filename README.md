# Advanced Linear Regression Assignment
> This analysis aims to give us an idea of using Ridge and Lasso Regression in a real business scenario. In this prediction analysis, we develop a basic understanding to evaluate the significance of parameters which impact the demand or the business.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
### Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.


### Business Goal:
To create a model to predict the price of houses with the available independent variables, which will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
Comparing the overall performance of Ridge and Lasso Regression, it is evident that Lasso performs slightly better than Ridge and also provide feature elimination.

The top predictor variables of Lasso model that are significant in predicting house price are:

- GrLivArea - Above grade (ground) living area square feet 

- OverallQual - Rates the overall material and finish of the house (10 - Very Excellent,  9 - Excellent, 8-Very Good)

- TotalBsmtSF - Total square feet of basement area 

- BsmtFinSF1: Type 1 finished square feet

## Technologies Used
- Numpy - version 1.20.3
- Pandas - version 1.3.4
- Seaborn - version 0.11.2
- Matplotlib - version 3.4.3
- Statsmodels API - version 0.12.2
- Scikit-learn - version 0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- https://pandas.pydata.org/docs/
- https://numpy.org/doc/stable/
- https://seaborn.pydata.org/
- https://matplotlib.org/
- https://www.statsmodels.org/
- https://scikit-learn.org/

## Contact
Created by
Nazneen Ansari [@nazneenansari]
