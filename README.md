# Bike Sharing Demand Prediction

## Problem Statement
Rental bikes have become a popular mode of urban transportation, aiming to enhance mobility comfort. Predicting the demand for rental bikes at each hour is crucial for ensuring a stable supply and reducing waiting times. This project focuses on predicting the count of bikes required per hour using various machine learning algorithms.

## Dataset Description
The dataset comprises weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), along with the number of bikes rented per hour and date information.

### Attribute Information:
- Date: year-month-day
- Rented_Bike_Count: Count of bikes rented at each hour
- Hour: Hour of the day
- Temperature: Temperature in Celsius
- Humidity: Percentage
- Windspeed: Meters per second
- Visibility: 10 meters
- Dew point temperature: Celsius
- Solar radiation: MJ/m2
- Rainfall: mm
- Snowfall: cm
- Seasons: Winter, Spring, Summer, Autumn
- Holiday: Holiday/No holiday
- Functional Day: NoFunc (Non-Functional Hours), Fun (Functional hours)

## Algorithms for Model Training
Several machine learning algorithms have been utilized for model training and prediction:

- Linear Regression
- Lasso Regression
- Ridge Regression
- KNeighborsRegressor
- Decision Tree Regressor
- GradientBoostingRegressor

### Boosting
Boosting is employed to improve predictive accuracy by converting multiple weak learners into a single strong learning model. GradientBoostingRegressor aggregates the results of each decision tree to calculate the final result, enhancing the model's accuracy.

## Conclusion
- The majority of bike rental customers are from the working class, leading to higher demand on weekdays.
- Bike rentals peak during the Summer season, followed by Autumn, Spring, and Winter.
- The Gradient Boost model achieved the highest predictive accuracy of 91.7%, outperforming other algorithms.

