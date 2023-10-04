# Surprise Housing Assignment for Advanced Regression



## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.


Also, determine the optimal value of lambda for ridge and lasso regression.
## Conclusions

The variables significant in predicting the price of a house are: -
GrLivArea, OverallQual_9, OverallCond_9, OverallQual_8, Neighborhood_Crawfor, Functional_Typ, Exterior1st_BrkFace, SaleCondition_Alloca, CentralAir_Y, TotalBsmtSF, Neighborhood_Somerst, TotalBsmtSF and Condition1_Norm

The top variables describe the price of the huse in the follow ways:
GrLivArea:an increase of 1 square foot of house area above ground, the price will increase by 1.09 to 1.11 times

OverallQual_9 & OverallQual_8: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.08 to 1.13 times

Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 1.07 to 1.09 times

Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.07 to 1.08 times

Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.07 to 1.08 times.

Optimal value of lambda for Ridge Regression = 10
Optimal value of lambda for Lasso = 0.001

## Contact
Created by [@debabrato] - feel free to contact me!

