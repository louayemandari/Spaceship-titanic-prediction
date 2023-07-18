# Spaceship-titanic-prediction


The Spaceship Titanic competition is a machine learning competition hosted on Kaggle. The goal of the competition is to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with a spacetime anomaly.

The dataset for the competition consists of two files:

train.csv: This file contains personal records for about two-thirds (~8700) of the passengers. This data can be used to train machine learning models to predict whether a passenger was transported to an alternate dimension.
test.csv: This file contains personal records for the remaining one-third (~4300) of the passengers. This data cannot be used to train machine learning models, but it can be used to evaluate the accuracy of the models that are trained on the train.csv file.
The features in the dataset include:

PassengerId: A unique identifier for each passenger.
HomePlanet: The planet the passenger departed from.
CryoSleep: Whether the passenger elected to be put into suspended animation for the duration of the voyage.
Cabin: The cabin number where the passenger is staying.
Destination: The planet the passenger will be debarking to.
Age: The age of the passenger.
VIP: Whether the passenger has paid for special VIP service during the voyage.
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck: The amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
Name: The first and last names of the passenger.
Transported: Whether the passenger was transported to another dimension. This is the target variable that you are trying to predict.


