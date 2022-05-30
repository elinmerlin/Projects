# Real Estate Price Prediction

The main task of the project is to predict the price of flats in Moscow.

The evaluation metric is Coefficient of determination.

#### File descriptions

train.csv - the training set

test.csv - the test set

sampleSubmission.csv - a sample submission file in the correct format

#### Data fields

Id - ID of the apartment

DistrictId - ID of the district

Rooms - number of rooms

Square - total area of the apartment

LifeSquare - living area of the apartment

KitchenSquare - kitchen area

Floor - floor 

HouseFloor - number of floors in the house

HouseYear - year the house was built

Ecology_1, Ecology_2, Ecology_3 - environmental indicators of the area

Social_1, Social_2, Social_3 - social indicators of the area

Healthcare_1, Helthcare_2 - indicators of the area, related to healthcare

Shops_1, Shops_2 - indicators of the area, related to availability of shops and malls 

Price - apartment price

#### ML model

Gradient boosting regressor

#### R2 on testing dataset 

0.74
