# Project Name
> Advance regression assignment - predicting sale prices of houses using advance regression techniques like ridge and lasso


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is a programming assignment wherein we built a advance regression model for the prediction of houses based on various variables.
- Background: A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.The company is looking at prospective properties to buy to enter the market. We need to build a regression model with regularization to predict the actual prices of the prospective properties.
- We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. This is the business problem we are trung to solve.
- Dataset used is train.csv which has 1460 rows and 81 columns.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Ridge regression model with alpha = 2 gave the best result, although ridge (alpha=1), lasso(alpha=50) and lasso(alpha=100) were pretty close in terms of r2 score for both train and test data
- A simple linear regression model with features eliminated through RFE would have worked as well, but lasso and ridge worked better.
- Final model: SalePrice = 66868xGrLivArea - 41866xCondition2 PosN - 41866xOverallQual Very excellent + 39953xTotalBsmtSF + 37064xGarageArea + 33881xBsmtFinSF1 + 27643xOverallQual Excellent + 26458xOverallQual Very good
- Cross validation shows aplha=1 would be better for ridge, but actual test result favoured ridge with alpha=2

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.9.12
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2
- scikit learn 1.0.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by @IamVib - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
