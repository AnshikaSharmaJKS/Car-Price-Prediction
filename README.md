# Car-Price-Prediction
Kaggle Competition ( Summer School Task-2) : 
Data taken from "https://www.kaggle.com/competitions/summer-school-2022-task-2/data".

Predicting the price of the car described by 14 metrics, which are as follows:-
seller =	private or dealer
offer_type	= type of offer
abtest	= a/b testing
vehicle_type	=   vehicle type
yearofregistration =	at which year the car was first registered
gearbox	= type of gearbox
power	= power of the car in PS
model	= model of the car
kilometer =	how many kilometers the car has driven
monthofregistration	= at which month the car was first registered
fuel_type	= type of fuel used by the car
brand =	manufacturer of the car
notrepaireddamage	= if the car has a damage which is not repaired yet
postal_code	= location details
price	= the price to sell the car

Exploratory Data Analysis and Feature Scaling.
Data Visualization : For finding outliers and importance of features.
Correlation Matrix to understand the correlation of features with the price of cars.
Splitted dataset in two sets:-
Training Dataset  70% of the dataset.
Validation Dataset  30% of the dataset.
Dataset trained on two models :-
SGDRegressor and RandomForestRegressor 
Hyperparameter tuning for best predictions on the models
Evaluation matrix: R2_score
Predictions in output csv file.
