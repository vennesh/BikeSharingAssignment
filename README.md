# Bike Sharing Assignment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
  Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, 
  and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents

Python is used in this case study.
Libraries Used: we have used Numpy, Pandas libraries for the coding and data manipulations and Matplotlib and seaborn libraries for visulalisation of the data to infer the insights.
and stats model and sckilearn for model building.


## General Information
Consider a bike sharing company that has a data set containing bike demands across the american market.

 Essentially the company wants:

   1. which variables are significant in predicting the demand for shared bikes.
   2. How well those variables describe the bike demands.


## Conclusions
  1. A unit increase in temperature then bike hire number increases by 0.5687 units.
  2. A unit increase in wea_3 then bike hire number decreases by 0.2541 units.
  3. A unit increase in yr then bike hire number increases by 0.2337 units.
  4. A unit increase in holiday then bike hire number decreases by 0.0871 units.
  5. A unit increase in windspeed then bike hire number decreases by 0.1453 units.
  6. A unit increase in mnth_9 then bike hire number decreases by 0.0891 units.
  7. A unit increase in sea_2 then bike hire number decreases by 0.0802 units.
  8. A unit increase in sea_4 then bike hire number decreases by 0.1275 units.
  
  Equation of fitted model is:
  
  cnt = 0.0872+(yr x 0.2337)+(holiday x -0.0871)+ (temp x 0.5687)+(windspeed x -0.1453)+ (mnth_9 x 0.0891)+(sea_2 x 0.0802)+ (sea_4 x 0.1275)+(wea_3 x -0.2541)


## Technologies Used
Numpy
Pandas
Matplotlib
Seaborn
StatsModel
Sckilearn
RFE


## Contact
Created by [@vennesh@github.com] - feel free to contact me!


