# Houses_Price_Prediction
#### Note: If you can't see the notebook here, prove clicking this link: https://nbviewer.jupyter.org/github/DanielAndres1116/Houses_Price_Prediction/blob/main/House%20Sales_in_King_Count_USA%20%284%29.ipynb

### Dataset Description

The dataset used contains house sale prices for King Vounty, which includes Seattle. It includes homes sold between May 2014 and May 2015 and it has useful data as: number of bedrooms, number of bathrooms, square footage of the home, square footage of the lot, total floors, built year, condition, price, between others.

### Objectives

The objective is analyze the dataset, make data wrangling to preprocess the dataset, view the data that could be useful for a machine learning model and finally predict house's price and use R-squared as evaluation metric to see if the model is working well. 

For the analyzis of data, was used graphical options as Boxplots and Scatter plots to have a better idea of how affects certain variables to the price which is the target variable in the model. Also was used methods to see the correlation that exists between the variables with the price. 

It was deployed Simple Linear Regression and after Multiple Linear Regression to identify what model works better. 

All this process is described in detail in the notebook. 

### Results and Conclusions

#### For the training model:

For a simple linear regression I got a R-squared of 0.49

For a Multiple Linear Regression I got a R-squared of 0.65

For a Multiple Linear Regression with a model constructor in which there is Standard Scaler I got 0.75, being this the better option. 


#### With model evaluation and Refinement

Separating the data between testing data and training data, I got a R-squared equal to 0.70

All this mean that it's possible get a good approximation of the House's price due its characteristics.



