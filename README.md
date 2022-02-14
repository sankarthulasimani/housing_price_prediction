# Prediction Of house price
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. From which it requires to predict the prices.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


#### Buisness Goal
It will be used by the management to understand how exactly the demands vary with different features.They will know

* Which variables are significant in predicting the price of a house, and

* How well those variables describe the price of a house.

This will be done with a model which is built with the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. Ridge and Lasso Regeression

## Conclusions
Top 10 Variables Significant in Predicting the house Price and their magnitude on how well they describe the price
##### As per Ridge Model:

* Neighborhood_Crawfor :0.3512
* BldgType_Twnhs :0.3490
* MSZoning_FV :0.2804
* BldgType_Duplex :0.2606
* OverallQual :0.2548
* GrLivArea :0.2364
* Neighborhood_NridgHt :0.1964
* MSZoning_RL :0.1844
* selling_Age : -0.1763
* BsmtExposure_Gd :0.1743

##### As per Lasso Model:

* Neighborhood_Crawfor :0.3217
* GrLivArea :0.2942
* Neighborhood_StoneBr :0.2902
* Exterior1st_BrkFace :0.2108
* MSZoning_FV :0.1850
* OverallQual :0.1696
* Neighborhood_BrkSide :0.1628
* Neighborhood_MeadowV : -0.1569
* SaleCondition_Normal :0.1454
* selling_Age : -0.1424

##### Optimal Value of Lambda for Lasso and Ridge are,
* Lasso : 0.0008
* Ridge : 4.0

##### Best model and model parameters
Lasso Seems to have better train and test R2 value,
R2 Score for training data: 0.9405093314944781
R2 score for Test data: 0.8955132345880263


## Technologies Used
- Python 3
- Numpy
- Pandas
- Seaborn
- Matplotlib
- scikit-learn


## Acknowledgements
- This project was done as an Assignment from Upgrad for linear regression module


## Contact
Created by <br>
<a href="https://github.com/cskn1097">@cskn1097</a> - - feel free to contact me! <br>