#Bike Sharing Demand Prediction

#Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

#Describing DataSet
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

#Attribute Information:
Date : year-month-day
Rented_Bike_Count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity - %
Windspeed - m/s
Visibility - 10m
Dew point temperature - Celsius
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

#Algorithms for Model Training
A model defines the relationship between features and label.A feature is an input variable—the x variable in simple linear regression.A label is the thing we're predicting—the y variable in simple linear regression.Training means creating or learning the model.In order to build the predictive model, it's time to implement some of the model training on the above selected feature.
Following algorithms have been used for predictions:-

Linear Regression
Lasso Regression
Ridge Regression
KNeighborsRegressor
Decision Tree Regressor
Boosting
Boosting is a method used in machine learning to reduce errors in predictive data analysis.Boosting improves machine models' predictive accuracy and performance by converting multiple weak learners into a single strong learning model. Machine learning models can be weak learners(have low prediction accuracy, similar to random guessing,prone to overfitting) or strong learners(higher prediction accuracy). Boosting converts a system of weak learners into a single strong learning system. There are many boosting algorithms which impart additional boost to model’s accuracy:
- GradientBoostingRegressor - aggregates the results of each decision tree along the way to calculate the final result

#Conclusion: 
--> Within the bike rental industry, the majority of customers belong to the working class. The exploratory data analysis indicates that bike demand is notably higher on weekdays, aligning with people's work schedules in Seoul.

--> Bike rentals reached their peak during the Summer season, followed by Autumn, Spring, and Winter. The most bustling period for bike rentals spans from May to July, while the months with lower popularity are December through February.

--> The linear model's predictive performance remained limited due to the weak linear correlation between features and labels. Achieving an accuracy of 91.7%, the Gradient Boost model emerges as the most accurate predictor.
