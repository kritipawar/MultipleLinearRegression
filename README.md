# Multiple Linear Regression - Bike Sharing Case Study
#### Problem Statement:

To model the demand for shared bikes with the available independent variables. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The Rental Company wants
-   to understand how exactly the demands vary with different features.

-   accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

-   understand the demand dynamics of a new market.


Dataset has daily records of bike rentals along with season, month, temp and other details.

## Model Summary
- R-Squared score on Train set:  0.83
- Adjusted R-Squared score on Train set:  0.82
- R-Squared score on Test set 0.79

## Conclusions
We can include few things to make our model better than current: 
1. Try building non-linear model
2. Add new features as geolocation, pincode, city etc

Model Insights:
1. Positive relation with year. It shows bike rental has increased over the year.
2. Strong positive relation with feeling temperature.
3. Negative relation with windspeed & spring season.
4. 0 rentals in rainy season

Business Insights:
- Business should make more bike available during april to Sept excluding rainy seasons.


## Technologies Used
- numpy
- matplotlib.pyplot
- pandas
- sklearn
- statsmodels.api
- seaborn


## Contact
Created by [@kritipawar] - feel free to contact me!
