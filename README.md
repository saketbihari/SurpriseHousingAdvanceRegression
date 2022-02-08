# Surprise Housing Advance Regression
> A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. 
You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project performs the exploratory data analysis on the housing dataset from Surprise housing.
Prepares a linear regression model and checks the r2 score, RSS and RMSE.
This project does regularization using Ridge and Lasso Regression and calculates the optimum value of Ridge and Lasso.
It compares the r2 score, RSS and RMSE for Ridge and Lasso regression.
It also compares the model coefficients for Ridge and Lasso regression and identifes to 10 predictor variable.



## Conclusions
- Optimal value of alpha for: Ridge = 0.5 and Lasso = 0.0001
- R2 score for train data for Ridge =0.914
- R2 score for test data for Ridge = 0.883
- R2 score for train data for Lasso =0.914
- R2 score for test data for Lasso = 0.884
- Top 10 features are :
	1stFlrSF : First Floor square feet
	OverallQual : Overall material and finish of the house
	2ndFlrSF : Second floor square feet
	MSZoning_RL : Residential Low Density Zoning
	MSZoning_FV : Floating Village Residential zo
	MSZoning_RH : Residential High Density zoning
	MSZoning_RM : Residential Medium Density zoning
	BsmtFinSF1 : Type 1 finished square feet
	OverallCond : Overall condition of the house
	GarageArea : Size of garage in square feet


## Technologies Used
- pandas - version 1.2.4
- numpy - version 1.20.1
- matplotlib - version 3.3.4
- seaborn - version 0.11.1


## Acknowledgements

- References
	Upgrad course

## Contact
Created by [@saketbihari] - feel free to contact me!


