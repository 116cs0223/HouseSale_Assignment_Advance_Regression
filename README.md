#  Name
>A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:
1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.
3. Determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used) 
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Here we have to create a linear regression model, Ridge Regression model and Lasso Regression model for the probelem statement.
- I am required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The objective of this project is to analyse the dataset and come up with a advance regreassion model to predict house sale on australian market on basis of learning on US data.

- The proivided dataset has different fields like MSSubClass, MSZoning,LotArea, LandContour,Neighborhood, YearBuilt,MasVnrArea,Foundation.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Both Ridge and Lasso model perform slightly better than linear regression model and give higher test score. Lasso model outperforms Ridge if compared. Hence the best model choosed is Lasso. The alpha value at which Lasso performs best is 0.0001.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- seaborn 0.11.2
- pandas 1.0.3
- numpy 1.15.4
- scikit-learn 0.20.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the Advance Regression Course conducted by IIITB and UpGrad.  



## Contact
Created by @116cs0223 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
