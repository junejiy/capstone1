# Capsone Project 1
# Predict errors of Zillow’s estimated home value

The goal of the project is to build a model to predict “logerror” which is the difference between the Zillow’s estimated home value, Zestimate, and the actual sale price.

            logerror=log(Zestimate)−log(SalePrice)

It is to improve the Zestimate’s residual error by predicting where zestimates will do good or bad. When we want to improve existing model, modeling errors can be a good way to find areas to improve the existing model. 


Data: 
The data used in the project has been provided from Zillow through Kaggle.com. The data is found at :
https://www.kaggle.com/c/zillow-prize-1
The following two files were used in the project. 

properties_2016.csv: The full list of real estate properties in three counties  (Los Angeles, Orange and Ventura, California) data in 2016. The dataset covers a wide range of information, including 59 features such as the building framing type, area of the lot in square feet, zip code , total property tax and etc.  

train_2016.csv: all the transactions before October 15, 2016, plus some of the transactions after October 15, 2016. It contains parcel ID ,  transaction date and calculated log error . 

Approach: 

Linear Regression
Random Forest
Gradient Boosting Regressor
Lasso

Deliverables:
Code
Report
Slide
