# Project Name
> We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)



## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know the following things about the prospective properties:

   - `Which variables are significant in predicting the price of a house`, and

   - `How well those variables describe the price of a house`.

- Also, determine the `optimal value of lambda for ridge and lasso regression`.


## Technologies Used
- library- pandas 1.3.4, numpy 1.20.3, matplotlib 3.4.3, seaborn 0.11.2, scikit-learn 0.24.2


## Conclusions
`'OverallQual_9'& 'OverallQual_8'` - if the overall material and finish of the house is **Very Good** or **Excellent**, the price of house will increase by 1.08 to 1.12 times<br>
`GrLivArea` - an increase of 1 square foot of house area above ground, the price will increase by 1.08 to 1.1 times<br>
`'Neighborhood_Crawfor'` - **Crawfor** Neighborhood predicts an increase by a factor of 1.08 <br>
`'Functional_Typ'`- **Typical Functionality** homes resonate with an increase of 1.06 times the house price<br>
`'TotalBsmtSF'`- Size of the basement impact the house price by 1.06 times<br>
`'Exterior1st_BrkFace'`- if the exterior covering on the house is **Brick Face**, the price of house will increase by 1.06 times.<br>
`'SaleCondition_Normal'`- **Normal** sale house has an impact of 1.05 to 1.06 times on the price of the house<br> 
`'BsmtCond_Gd'`- **Good** condition house depict the pricing by a factor of 1.04 to 1.05 times<br>




## Contact
Created by [@abhinavforanalytics]