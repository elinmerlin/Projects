# COVID-19 Death prediction
From Kaggle competition https://www.kaggle.com/competitions/Covid19-Death-Predictions

The goal is to predict the next week's deaths from COVID-19 for a region.

The evaluation metric is RMSE.

#### File descriptions

- train.csv - the training set
- test.csv - the test set
- ampleSubmission.csv - a sample submission file in the correct format

#### Data fields

- Columns
- Id => Unique id for each row
- Location => Name of the country/region/group of people
- Year => Year of the start of the week is in
- Weekly Cases => Weekly new confirmed cases of COVID-19
- Weekly Cases per Million => "Weekly Cases" per 1,000,000 people in the total population of the location
- Weekly Deaths => Weekly new deaths attributed to COVID-19
- Weekly Deaths per Million => "Weekly Deaths" per 1,000,000 people in the total population of the location
- Next Week's Deaths => Weekly Deaths for the next week
- Total Vaccinations => Total number of doses administered
- People Vaccinated => Total number of people who received at least one vaccine dose
- People Fully Vaccinated => Total number of people who received all doses prescribed by the initial vaccination protocol
- Total Boosters => Total number of COVID-19 vaccination booster doses administered 
- Daily Vaccinations => New doses administered per day (7-day smoothed)
- Total Vaccinations per Hundred => "Total Vaccinations" per 100 people in the total population of the location
- People Vaccinated per Hundred => "People Vaccinated" per 100 people in the total population of the location
- People Fully Vaccinated per Hundred => "People Fully Vaccinated" per 100 people in the total population of the location
- Total Boosters per Hundred => "Total Boosters" per 100 people in the total population of the location
- Daily Vaccinations per Hundred => "Daily Vaccinations" per 100 people in the total population of the location
- Daily People Vaccinated => Daily number of people receiving a first COVID-19 vaccine dose (7-day smoothed).
- Daily People Vaccinated per Hundred => "Daily People Vaccinated" per 100 people in the total population of the location

#### ML model

Cat Boost Regressor

#### RMSE on testing dataset 

284 
