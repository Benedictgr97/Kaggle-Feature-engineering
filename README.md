# Kaggle-Feature-engineering
Predicting the review score of a range of Saudi hotels given their price and descriptions.

Due to the course focusing on feature engineering, this is the main focus of the exercise. A large amount of dummy variables are produced for the 3 descriptive columns,
room type, cm and beds. Other values such as price, beds and people a night where extracted and modified to find price per person and price per bed. Both of these modified 
values decreased the mean absolute error. PCA however, failed to decrease the MAE due to useable values not being highly correlated. XGboost was used for all models due to 
the datset being small.
