# BoomBikes-bike-sharing-assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.
The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- plotly - version 5.6.0
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2


## Conclusions
- By using the above scatter plot and the parameters , We can see that the equation of our best fitted line is:
cnt = 0.202 + 0.242* yr + 0.047* workingday + 0.429* atemp - 0.079* windspeed - 0.274* weathersit_bad - 0.084* weathersit_moderate - 0.161* season_spring + 0.083* season_winter - 0.069* mnth_dec - 0.048* mnth_jul + 0.052* mnth_mar - 0.085* mnth_nov + 0.051* mnth_sept + 0.054* weekday_saturday

- Year, workingday, atemp, windspeed, weathersit(bad & moderate), season(winter & spring) month(december, july, march, november, september) & weekday saturday are significant features to predict the demand for shared bikes

- All the positive coefficients like yr, workingday, atemp, windspeed, season_winter, mnth_march, mnth_sept & weekday_saturday indicate that an increase in these values will lead to an increase in the value of cnt.

- All the negative coefficients indicate that an increase in these values will lead to a decrease in the value of cnt.

- From R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 81% of bike demand.

## Recommendations 
- The months - march & september should be considered by the company as they have a higher demand as compared to other months.
- With an increase in temperature the demand also increases, hence it should keep track of the weather conditions.
- During the Winter season the demand rises, hence it should be well prepared to meet the high demand.
- Demand decreases for bad & moderate weather condition.
- Holiday time seems to be least interesting for biking, little motavation and marketing might help here

## Contact
Created by [@deepalipardhe] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
