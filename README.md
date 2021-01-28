# Flats - building model
Model Building for flats price prediction. First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.
I tried five different models and evaluated them using Mean Absolute Error. I chose MAE because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model.
I tried five different models:
*	**Simple Linear Regression** 
*	**Multiple Linear Regression**
*	**Gradient Boost Regression** 
*	**Lasso Regression** 
*	**Random Forest**
## Model performance
The Random Forest model and Multiple Linear Regression far outperformed the other approaches on the test and validation sets. 
*	**Multiple Linear Regression** : MAE = 5246.74
*	**Random Forest** : MAE = 5536.21
*	**Lasso Regression**: MAE = 41405.14
*	**Gradient Boost Regression** : MAE = 68813.31
*	**Simple Linear Regression** : MAE = 101789.11
