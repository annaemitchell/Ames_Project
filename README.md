# Predicting Housing Prices in Ames, Iowa
***

Anna Mitchell
***

### Executive Summary
There are many possible indicators that might drive up or down housing prices. We have over 80 possible indicators which can influence housing prices. This information can help buyers to look for the right kind of feature in a house or even help home owners and property companies better price them. When using the right kind of predictors, the models aim to make the property market in Ames a fair and competitive one that will benefit both buyers and sellers. 

### EDA and Cleaning Notebook

**Table of Contents**
* Load Data
* Garage Variables
* Size Variables
* Quality Variabes
* Access Variables
* Land Variables
* Utilities Variables 
* Remaining Variables
* Modifying Test Data Set
* Data Cleaning 


### Modeling Notebook

**Table of Contents**

* Import Libraries and Read Data
* Distribution of Home prices by Quality
* Multiple Linear Regression (Model 1)
* Lasso Regression (Model 2)
* Ridge Regression (Model 3)

### Approach
My approach was to first build a standard linear regression model using the numeric columns in the dataset, and upload an initial prediction. My first attempt was to beat my baseline score. Using the techniques we have learned in class to date, I selected features to include or exclude, analyzed the scores of each model, and made revisions to see if I could improve. This project details the steps in the process, and is summarized with a final report that provides details about which features are most important in predicting home prices. 


### Conclusion and Next Steps

The model did tell us which features it determined were most predictive, which begins to answer the question of what features are most important for predicting home prices. It suggests that while location is important, size and quality are the most important. More could be done, to improve my model. I would like to do a deeper exploration in other variables, and try to incoporate a series of piplines to make it easy to build and trest these models in batch. 
