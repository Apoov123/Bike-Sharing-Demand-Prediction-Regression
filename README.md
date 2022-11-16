# Bike-Sharing-Demand-Prediction-Regression

## Problem Statement

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Data Pipeline

● Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

The key takeaway from the EDA and Modeling are-

* Bike rental count is strongly correlated with the time of the day, with weaker dependence on the temperature and humidity.

* There are 2 rental patterns across the day in bike rentals count-

    1) On a Working Day where the rental count high at peak office hours (8am and 5pm) and
    
    2) On a Non-working day where rental count is more or less uniform across the day with a peak at around noon.
   
        
● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

● Data Processing: In this part we went through each attributes and encoded the categorical features.

## Observations

● 1: In the Model Evaluation Matrices table, Linear Regression is not giving great results.

● 2: Random forest & GBR have performed equally good in terms of adjusted r2.

● 3: We are getting the best results from Gradient Boost Ensemble Technique.

## Conclusions

● We started with loading the data, then we did Exploratory Data Analysis (EDA), null values treatment, feature selection, encoding of categorical columns, and then model building. In all of these models, our accuracy ranges from 56% to 91%, which can be said to be good for such a large dataset. This performance could be due to various reasons like the proper pattern of data, large data, or because of the relevant features.

● After performing variable importance analysis to find the most significant variables for all the models developed with the given data sets. We are getting the best results from Random Forest Ensemble technique and Gradient Boosting technique.



