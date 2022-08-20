# Problem Statement

Flight ticket costs can be difficult to predict; while we may see a price today, when we check the cost of the same flight tomorrow, it will likely be different. Perhaps you've heard passengers complain frequently about how unpredictable the cost of airline tickets is. We will demonstrate as data scientists that anything can be predicted given the correct data. You can get pricing for flights on different airlines between different cities during the months of March and June 2019 right here.
Training set size: 10683 records

## Dataset Details

The dataset for the project is taken from Kaggle, it is a time-stamped dataset, extensive pre-processing was done on the dataset especially on the date-time columns to finally come up with a ML model which could effectively predict airline fares across various Indian Cities. The various independent features in the dataset were:

## Model Building

First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 30%.

I tried six different models and evaluated them. using r2_score.

## Model Accuracy

GradientBoostingRegressor
- 0.581642












