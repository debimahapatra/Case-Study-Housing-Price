# Project Name
> House SalePrice Case Study


## Table of Contents
* [Problem Statement](#problem-statement)
* [Assumptions](#assumptions)
* [Technologies Used](#technologies-used)
* [Final Model](#final-model)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)


## Problem Statement
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know: Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.
- Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Assumptions
- NA


## Technologies Used
- Language - Python
- library - Numpy
- library - Pandas
- library - matplotlib
- library - seaborn
- library - math
- Library - statsmodel
- Library - sklearn

## Final Model
- Lasso Model is the final model
- I will choose Lasso over other models:
    -Lower RSS values
    -Difference between Test and Train R2 Square is lower
    -Higher R2 Square value for both Train and Test

## Conclusions

-The metrics associated with all the three model looks like below:

-Metric Linear Regression Ridge Regression Lasso Regression 0 R2 Score (Train) 9.482163e-01 0.904921 0.912440 1 R2 Score (Test) -2.559119e+19 0.799586 0.825604 2 RSS (Train) 4.683346e-01 0.859902 0.791900 3 RSS (Test) 1.482065e+20 1.160661 1.009981 4 MSE (Train) 2.444106e-02 0.033118 0.031782 5 MSE (Test) 6.641466e+08 0.058774 0.054826

-Lambda Values: Optimum Alpha value for Ridge and Lasso Alpha value for ridge: 6 Alpha value for lasso: 0.0001

-I will choose Lasso over other models:

    -Lower RSS values
    -Difference between Test and Train R2 Square is lower
    -igher R2 Square value for both Train and Test

-R2 Square on Train data for Lasso Model is 0.91244 So, 91% of the variation can be explained by the Lasso model

-Top five impactfull predictors: 
    -GrLivArea 
    -PoolQC_Gd 
    -OverallQual 
    -RoofMatl_WdShngl 
    -MasVnrArea


## Acknowledgements
- This project is part of a case study from Upgrad for identification of key parameters affecting house price


## Contacts
- Created by [@debimahapatra]
