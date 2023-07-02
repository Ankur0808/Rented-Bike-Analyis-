# Rented-Bike-Analysis-
# Superivised Machine Learning- Regression 

### <b>Attribute Information: </b>

* ### Date : year-month-day
* ### Rented Bike count - Count of bikes rented at each hour
* ### Hour - Hour of the day
* ### Temperature-Temperature in Celsius
* ### Humidity - %
* ### Windspeed - m/s
* ### Visibility - 10m
* ### Dew point temperature - Celsius
* ### Solar radiation - MJ/m2
* ### Rainfall - mm
* ### Snowfall - cm
* ### Seasons - Winter, Spring, Summer, Autumn
* ### Holiday - Holiday/No holiday
* ### Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Conclusions:
* #### As we have calculated MAE, MSE, RMSE, and R2 scores for each model. Based on r2 score will decide our model performance.
* #### Our assumption: if the difference in R2 score between the Train data and the Test is more than 5 % we will consider it as overfitting. 

* ## Linear, Lasso, Ridge, and ElasticNet.
* #### 1) Linear, Lasso, Ridge and Elastic regression models have almost similar R2 scores(61%) on both training and test data. (Even after using GridserachCV we have got similar results as of base models).

## Decision Tree Regressor:
> * #### On the Decision tree regressor model, without hyperparameter tuning we got an r2 score of 100% on training data, and on test data, it was very less. Thus our model memorized the data. So it was an overfitted model.
* #### After hyperparameter tuning we got an r2 score of 88% on training data and 83% on test data which is quite good for us.

## Random Forest:

> * #### On the Random Forest regressor model, without hyperparameter tuning we got an r2 score of 98% on training data and 90% on test data. Thus our model memorized the data. So it was an overfitted model, as per our assumption
* #### After hyperparameter tuning we got an r2 score of 90% on training data and 87% on test data which is very good for us.

## Gradient Boosting Regression(Gradient Boosting Machine):

* #### On the Random Forest regressor model, without hyperparameter tuning we got an r2 score of 86% on training data and 85% on test data. Our model performed well without hyperparameter tuning.
* #### After hyperparameter tuning we got an r2 score of 96% on training data and 91% on test data, thus we improved the model performance by hyperparameter tuning.

 **Thus Gradient Boosting Regression(GridSearchCV) and Random forest(gridSearchCv) gives good r2 scores. We can deploy this model.**
 

