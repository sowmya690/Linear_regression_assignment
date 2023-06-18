# Linear Regression Assignment - Bike Sharing
Build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* [About the company](#About-the-company)
* [Problem Statement](#Problem-statement)
* [Conclusions](#Conclusions)   
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## About the company
BoomBikes is a US bike-sharing provider. A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system services company headquartered in San Francisco, California. That explains the business model.

## Problem statement
BoomBikes has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. Company want to understand the factors affecting the demand for these shared bikes in the American market. Mainly the company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

input :
day.csv file which contains the previous bikesharing data set
Readme.txt which contains the meta data information of day.csv file


- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Equation for best fit line is

cnt = 0.2347 + (0.2534 * yr) + (0.4237 * temp) - (0.0380 * windspeed) - (0.1591 * season_spring) + (0.0096 * summer_season) + (0.0634 * season_Winter) - (0.0489 * mnth_July) + (0.0466 * mnth_Sep)- ( 0.0311 * weekday_Sun) - (0.2687 * weathersit_Light Snow) - (0.0748 * weathersit_Mist + Cloudy)

Recommendations to Boom Bike's bike
- The temperature variable has the highest coefficient 0.4237, which means if the temperature rises by 1 unit, the number of bike rentals increases by 0.4237
- The Light Snow and the Mist+Cloudy variables have negative coefficients, which means a reduction in bike rentals
- The windspeed variable also has a negative coefficient, which means a reduction in bike rentals with increase in the windspeed
- Spring season has negative coefficients, so the company can run some discount offers to attract the customers to book more
- Sunday is seeing a drop in bookings so the company can run some promotional events in and around parks and leisure spots

## Technologies Used
- python
- pandas library
- matplotlib library
- numpy library
- seaborn library
- sklearn library
- statsmodels library

## Acknowledgements
Give credit here.
- This project was inspired by upGrad's assignment

## Contact
Created by [@sowmya690] - feel free to contact me!

