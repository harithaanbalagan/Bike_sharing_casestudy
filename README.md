# Bike_sharing_casestudy
> Bike_sharing_casestudy using Linear Regression.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Problem Statement
	A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
	A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
	In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
	They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
	-Which variables are significant in predicting the demand for shared bikes.
	-How well those variables describe the bike demands
	-Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


-Business Goal:
	You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- Here the goal is understanding different indepent variable which improves the bike rentals
- The dataset being used is day.csv



## Conclusions
-In fall there seems to be highest demand of bikes, followed by Summer and Winter,Spring seems to be the least season where demand is less
-average rented bikes has increased in 2019 almost double of 2018
-More and almost similar average count of rented bikes in August, June, September, July followed by May, October.
	December, January, February have the least demand
-looks like all days have similar demands, but still Sunday, Monday, Saturday, Friday has high demands than other days
	People less prefer rented bike on Thrusday, Wednesday,Tuesday
-There are similar demands whether it's a working day or not.
-It clearly shows that if the weather is clear, the demand is more
	If the weather is bad, demand decreases drastically
-As per my final Model, the below predictor variables influences bike booking :
	Temperature (temp)
	September Month
	Year -2019
	Summer Seaon
	Winter Season
	If its a holiday
	If the weather is clear/Good
	Speed of the Wind

## Technologies Used
library - Pandas,Numpy,Matplotlib,Seaborn,Sklearn,statsmodels.api






