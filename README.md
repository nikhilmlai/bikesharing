# Bike Sharing Assigment Solution
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

The company wants to know: 1. Which variables are significant in predicting the demand for shared bikes. 2. How well those variables describe the bike demands

The solution is divided into the following sections:

1. Data Exploration
2. Data Visualisation
3. Data Preparation
4. Model Building and Evaluation

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project explores the given dataset to idenify driving factors for Bike Rentals 
- The data used for the analysis is for year 2018 & 2019
- The data is collected against various variables like:
	- Season - Spring, Summer, Fall, Winter
	- Month - Jan - Dec 
	- WeatherSit - 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog)
	- Temprature
	- Humidity
	- Wind Speed
- With this porject we are trying to indentify key variables which are significantly influnecing Daily Bike Rentals for the organization 

## Conclusions
- 1 : Temperature is most significant variable for the Bike Rental Higher the temparature higher will count of bikes on the rental
- 2 : The bussiness of Bike Rental will improve over the period of time as we can figure out that 2019 has done more bussiness compared to 2018. So year in year business will improve
- 3 : Weathersit Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds also plays reverse significance on the daily bike rentals

## Technologies Used
- Pandas - For Data Manipulation
- seaborn - For Data Visualization
- matplotlib - For Data Visualization
- statsmodels - Stats Model for building the model
- Scikit Learn - SciKit Learn used For
	- Train & Test Data Split 
	- Modeling Building using Linear Regression, RFE 
	- Calulation of Matrics like MSE, R2 Square
	- Perform Residual Analysis

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@nikhilmlai] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
