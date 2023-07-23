# Bulldozer-price-predictor
## 1.Problem Definition
How well can we predict the future sale price of a bulldozer,given its characteristics and previous examples of how much similar bulldozers have been sold for?

## 2.Data
The data is downloaded from the kaggle Bluebook fir Bulldozers competition:https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

There are 3 main datasets:

Train.csv is the training set, which contains data through the end of 2011.

Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

Test.csv contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## 3.Evaluation
The evaluation metric for this project is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

## 4.Modelling and Improving our model
The model has been trained on the RandomForestRegressor and has been improved using the RandomizedSearchCV and GridSearchV.
