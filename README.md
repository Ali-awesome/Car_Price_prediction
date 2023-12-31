# Car_Price_prediction

### Metadata

- make:- Manufacturer Name with number of unique values: 48
- model:- Build Model with number of unique values: 914
- year:-  Build year with number of unique values: 28
- engine_fuel_type:- Type of fuel needed with number of unique values: 10
- engine_hp:- How much horse power engine produces with number of unique values: 356
- engine_cylinders:- How many cylinders engine contains with number of unique values: 9
- transmission_type:- How gear transmission works with number of unique values: 5
- driven_wheels:- How many drive wheel produce tork with number of unique values: 4
- number_of_doors:- Number of doors available with number of unique values: 3
- market_category:- What kind of status car holds with mumber of unique values: 71
- vehicle_size:- How much spacious car is with number of unique values: 3
- vehicle_style:- What kind of style the car holds with number of unique values: 16
- highway_mpg:- Miles per gallon in Highway with number of unique values: 59
- city_mpg:- Miles per gallon in City with number of unique values: 69
- popularity:- How much popular the car is with number of unique values: 48
- msrp:- Manufacture's suggested retail price with number of unique values: 6049

### Overview
In this project we have done following things:-
- After taking a overview of the dataset we have eliminated inconsistencies.
- At EDA stage we have dealt with missing values,
    - Target variable distribution was long tailed, transformed with log transformation into bell shaped curve
- Used a validation framework: train/val/test split (helped us detect problems)
- Built a Linear regression model for use.
- Used RMSE(Root Mean Squared Error) to validate our model.
- Feature engineering: age, categorical features to train our model.
- Regularization to fight numerical instability.
- Finally used the model and predicted the value of a car.