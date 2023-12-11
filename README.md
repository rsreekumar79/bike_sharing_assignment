# Bike sharing - predictive analysis of daily demand
> The aim of the project is to arrive at a multiple linear regression model using python and associated data analysis/regression/statistics libraries to predict the number of daily users(demand) of a bike sharing service. A data set with the data dictionary with around 700+ data points are provided for the analysis. The goal is to zero in on the influential variables and finally arrive at a regression model with an r2 score on the test data almost equal to the r2 score on the training data. The exercise is for a US based bike sharing business BoomBikes. The company aims to increase its revenue after the covid pandemic


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General Info: The project is to arrive at a reasonably good linear regression model able to predict the demand for bikesharing in terms of user numbers on a daily basis. A data set is provided with a datakey based on a survey. Predictive analysis to to be done to arraive at a best possible linear regression model considering the influential predictor variables from the data set or derived variables from the available data.
- Background: A US based bike-sharing company BoomBikes has recently observed severe reductions in their revenues due to the ongoing Corona pandemic. In the current market scenario, the company has to ramp up to sustain. Therefore a good business plan is requried to be able to increase the revenue once the lock down is revoked, and the economy restores to a healthy state. BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- Business Problem: it is required to model the demand(target variable) for shared bikes with the available independent variables(predictor variables). Management should be able to understand how the demand for shared bikes varies with these variables. accordingly business strategy can be manipulated to meet the demand levels and meet the customer's expectations. The model will help to predict demand ona new market as well.
- Dataset being used: Data set provided has variables pertaining to weather like temperature, humidity, windspeed, seasons, severity of the weather, month of the year, daily observations, seasons, whether the day is a holiday or a working day etc. The target variable is the number of daily users , sum of both registered as well as casual users.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model lrm5 is the chosen model with r2 score of  81%. A total of 7 different models were tried out, lrm to lrm6
- r2_Score on test data is also coming the same as 79.7%
- The variables considered in the model are
    - holiday: day of the week has a negative influence
    - atemp: real feel temperature also has a positive influence. This has the highest positive influence.
    - windspeed: negative influence. 
    - spring: spring weather has a negative influence
    - winter: winter has a positive influence
    - mild_weather: has positive influence(Clear, Few clouds, Partly cloudy, Partly cloudy)
    - strong_weather: has negative influence which is self explanatory(Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog)
    - year: year has apositive influence meaning 'cnt' target variable increases by year. The year 2019 after the covid-lock down and restrictions is seeing a jump in the bike sharing service demand

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python version 3.8.10
- pandas version 2.0.3
- numpy version 1.23.5
- seaborn version 0.13.0
- matplotlib version 3.5.3
- sklearn-crfsuite version 0.3.6
- statsmodels version 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- https://pandas.pydata.org/pandas-docs/stable/index.html
- https://numpy.org/doc/
- https://seaborn.pydata.org/
- https://plotly.com/python/plotly-express/
- https://matplotlib.org/
- https://scikit-learn.org/stable/index.html
- https://www.statsmodels.org/stable/index.html

## Contact
Created by Sreekumar R (https://github.com/rsreekumar79)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->