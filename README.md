# Project Name
Surprise Housing Company's Australian Merket entry Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.


The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

 

Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

#### Following are the 5 most important predictors identified by Ridge Regression 
1. TotalFloor_excluding_basement, 
2. OverallQual, 
3. TotalBathroom, 
4. Neighborhood_NoRidge, 
5. KitchenQual 

#### Following are the 5 most important predictors identified by Lasso Regression 
1. TotalFloor_excluding_basement, 
2. OverallQual, 
3. Neighborhood_NoRidge
4. KitchenQual 
5. TotalBathroom, 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

Python 3
sklearn
numpy
pandas
matplotlib
seaborn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was created as part of advanced regression Assignment 
- This project was based on [this tutorial](https://www.upgrad.com/ca/).


## Contact
Created by @sghoshca - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->