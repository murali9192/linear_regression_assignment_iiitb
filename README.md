# Linear Regression Assignment - Prediction on Bike Rentals
> This assignment aims to develop a Linear Regression model to predict the number of Bike Rentals that can be expected on the basis of various factors, in addition to understanding of the significance of these factors in effectively predicting the target variable.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- A simple assignment on utilization of Linear Regression.
- We use Python programming language for undertaking this task.
- We are intending to predict the bike rentals that can be expected on the basis of various factors. We also intend to understand the significance of these factors in predicting the Bike Rentals, so that the same can be used in Business Decision making.
- The dataset 'day.csv' file contains historical bike rental data that is to be used in building the Linear Regression model.



## Exploratory Data Analysis
### Categorical Variables
- Season 3 leads to significant increase in Bike Hires. Season 2 and 4 are average and Season 1 proves to be the least significant contributor towards Bike rentals.
- The average bike rentals are significantly higher in the second year compared to the first year. The demand tends to increase over time.
- The middle of the year, from April - October contribute to majority of bike rentals compared to the other months.
- Weather situation 1 contributes to huge number of Bike rentals, with Situation 2 also contributing a significant sum. Weather situation 3 proves to be a time during which the demand is extremely less.
### Continuous Variables
> On observing pairplot of numerical variables, the independent variables ‘registered’ and ‘casual’ have the highest correlation with the target variable. Especially, the majority of the users hiring bikes are registered users and hence the company should target to increase their registered user base. However, these two variables are mere distribution of the target variable, hence there is no surprise in observing significant correlation between them. Apart from these two independent variables, ‘temp’ and ‘atemp’ are the two independent variables that exhibit a positive linear relationship with the target variable.

## Conclusions
- On the basis of the final model, it can be concluded that the three variables 'workingday', 'casual' and 'Season4' significantly influence the outcome of the number of rentals obtained in a given day.
- Though, there are various factors such as temperature, humidity, etc. that play a role and tend to exhibhit a significant correlation with the target variable, there is a high possibility that they might be significantly correlated with the other independent variables leading to Multicollinearity. Hence, these variables have been removed from the model during the course of Model evaluation and optimization.
- The model has exhibited an Adjusted R Square of 0.96 on the tarining dataset, which is considered to be good.
- On Residual Analysis, the error terms exhibit a Normal Distribution satisfying the assumptions of Linear Regression. Also the Variance Inflation Factor values of the independent variables are found to be optimum.
- On testing of the model on the test dataset, R Square value of 0.67 has been achieved.





## Libraries Used
- Matplotlib and Seaborn for Visualization.
- Statsmodels and ScikitLearn for Analysis and Model Generation.


## Contact
Created by [@murali9192] - feel free to contact me!

