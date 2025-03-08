# BulldozerPricePrediction
To predict the future sale price of bulldozers
## 1. Problem Definition
> How well can we predict future sales price of bulldozers given historical price of same

## 2. Data
Data downloaded from kaggle bulldozer bluebook competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

It contains 3 main datasets:


* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* 
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competitio

## 3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

More info on evaluation evaluation available on: https://www.kaggle.com/c/bluebook-for-bulldozers/overview
goal of regression is to minimize error. Our goal here is building a model that minimizes RMSE

## 4. Features
As provided by kaggle: /bluebook-for-bulldozers/bluebook-for-bulldozers/Data Dictionary.xlsxn.
