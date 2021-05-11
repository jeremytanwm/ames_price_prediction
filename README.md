# Ames Housing Price Prediction


## Problem Statement

In this project, we analyse the Ames Housing Dataset provided from the Ames Assessor's Office to determine what features affect the sales prices of houses in Ames, IA. Through the development of an appropriate regression model, the sales prices of houses will be predicted using various features (variables) of houses from the Ames Housing Dataset.

Ultimately, we aim to provide a useful prediction model for real estate agents to predict house prices for their existing and potential clients, providing useful insights on the effect of different features on real estate prices through our model.


## Executive Summary

In this exploration, I utilize data from the Ames housing market to predict sale prices. The data represent the sale prices of various properties as well as many features of the property, such as overall quality, first floor square footage, lot frontage, and many others.

The main aim is to predict the sale price of the properties in Ames, Iowa with the given features using a linear regression model. With such model in place it allow us to find properties that are under value and use this information to provide investment advise for our clients. 

Our model has a accuracy of 89%. What it means is that 89% of the sale price predictions can be explained by the features that we selected in our model. Overall quality, ground living area, basement finishing are some of the most important determinant factors of sale price. 



## Conclusion

In conclusion, the model we build score a 0.899 as compared to the baseline score of 0.893. This shows that lasso regression model does a slightly better job predicting the prices than the linear regression model. This is expected as lasso regression aims to reduce overfitting by shinking or reduce down to zero on the features coefficient. 

By using feature engineering, feature elimination, regularization, and target variable transformation, we can reduce loss and greatly improve the performance of the model.

With this model in place, it will allow us to provide better investment advise such that if any houses on the market is valued below what we predicted, we BUY!



