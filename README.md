# Bike Sharing Assignment
> BoomBikes aspires to understand the demand for shared bikes among the people.
> BoomBikes wants to understand the factors on which the demand for these shared bikes depends. 
> Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.
	- Which variables are significant in predicting the demand for shared bikes
	- How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
	- This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.
- What is the dataset that is being used?
- =========================================
- Dataset characteristics
- =========================================	
	- day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered


## Conclusions
- The bike hire increases by **0.23 units** as an year on year growth
- The ***Working Day*** and ***Temperature*** impact the bikes being hired.
- The seasons of ***Summer*** and ***Winter*** impact the bikes being hired.
- The months of ***August***, ***September*** and ***October*** impact the bikes being hired.
- The weekday of ***Saturday*** impact the bikes being hired.
- The following climatic / weather condition impact the bikes being hired, **NEGATIVELY**
    - Humidity and Windspeed
    - Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    - Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python 3.9.12
- Excel 2021
- Word 2021
- Windows 11

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by...
- Linear Regression assignment in Executive PG Programme in Machine Learning & AI - December 2022


## Contact
Created by [@d6ic9y] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->