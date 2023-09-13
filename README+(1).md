# Bike Sharing Case Study
>
>EDA and modelling the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- Forecasting the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- The dataset inculdes three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number casual users who have made a rental. The variable 'registered' on the other hand shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model should be built taking this 'cnt' as the target variable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Month wise demand of share bikes stands minimum in the month of February
- Median value of demand of shared bikes is maximum in fall season followed by summer, winter and spring.
- Peak demand of shared bikes is in the month of September.
- Year 2019 has the maximum amount of demand in shared bikes compared to 2018
- Median value of demand on a non-holiday day is more compared to a holiday.
- Average and peak count of demand on clear cloud day is maximum followed by mist cloud and light snow.
- atemp and temp have a very high correlation and hence either of any one variabel can be dropped.
- Categorical variable converted to dummy variabel creation
- Based on correaltion, p-values, VIF & RFE, final varibels selected.
- Selected vaiabels: 8 independent variables and 1 derrived independent variable
- Model R^2:79.2, adjusted R^2:0.788
- Final variables considered for model: Year, Workingday, windspeed, summer, fall, winter, mist cloud, light snow and ratio Cas_reg.
- Final model variables p-value:0.00 and VIF:3.8(Max.)
- From the model, variabels such as fall, year and winter plays a dominant role in deciding the demand of the shared bikes.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Muti Linear Regresssion
- Autoviz for EDA
- RFE and VIF & p-values for variabel selection


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->





## Contact
Created by [@pradeepkr23] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
