# BoomBikes Linear Regression
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The Equation for best fitted line is -

cnt = 0.246 X yr - 0.083 X holiday - 0.198 X Spring - 0.321 X Light rain_Light snow_Thunderstorm - 0.090 X Mist_Cloudy + 0.063 X mnth_3 + 0.123 X mnth_5 +0.148 X mnth_6 +0.153 X mnth_8 + 0.193 X mnth_9 -0.049 X Sunday + 0.126 X mnth_7 + 0.116 X mnth_10

Below are the obersvation :

1. Demand of Bike depends manily on below variable :
yr , holiday ,Spring, Mist_Cloudy, Light rain_Light snow_Thunderstorm,mnth_3 , mnth_5 ,mnth_6, mnth_8, mnth_9, sunday, mnth_7, mnth_10.

2. Increase in demand is observed in the month of 3, 5, 6, 8 ,9, 7 , 10 and yr.
Demand decrease if it is Spring, holiday , Light rain_Light snow_Thunderstorm, Mist_cloudy and Sunday.

3. Finally Demand increases in the month of 3, 5, 6, 8 ,9, 7 , 10 and yr.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python   -  version 3.0
- Matplotlib
- Seaborn
- Sklearn
- Statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was created to explore and apply our linear regression learning.


## Contact
Created by ursharry@github.com - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
