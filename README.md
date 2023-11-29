# House Price Prediction
> Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price
- The company has collected a data set from the sale of houses in Australia
- The company is looking at prospective properties to buy to enter the market
- The company wants to know:
  Which variables are significant in predicting the price of a house, and 
  How well those variables describe the price of a house.
- This model will then be used by the management to understand how exactly the prices vary with the variables
- The model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Lambda values for Ridge and Lasso Regression are 50 and 500 respectively
- Ridge and Lasso Regression performed well than Linear Regression
- R2 scores for Ridge and Lasso are 0.73 and 0.72 respectively (on Test data)
  whereas Linear Regression had R2 score of 0.7 (on Test data)
- Lasso Regression provided feature elimination options
- With Lasso Regression following features were eliminated -
  BsmtUnSF, 2ndFlrSF, LowQualFinSF, 3SsnPorch, PoolArea, all_utilities, prox_NS, prox_adj, lot_inside, foundation_cinder, mansory_type_available, and 1_Story_1946
  - See Jupyter notebook for a list of significant variables in predicting the price of a house,
- The top 5 predictors in the Lasso model (before removing them) are – 
  - GrLivArea                
  - TotalBsmtSF              
  - GarageCars              
  - BsmtFinSF1                
  - LotArea       

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.24.3
- pandas - version 1.5.3
- seaborn - 0.12.2
- scikit-learn - version 1.2.2
- statsmodels - version 0.13.5


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- https://scikit-learn.org/stable/index.html


## Contact
Created by https://github.com/rk1989 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
