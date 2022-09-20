# MLR_BoomBike_sharing-
 
## Problem Statement:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## The goal of the study:
To Build a multiple linear regression model to predict the future demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 

We are intrested to know:
 - Which variables are significant in predicting the demand for shared bikes.
 - How well those variables describe the bike demands.


Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Summary:

Based on the analysis following conclusions were obtained:
- Total rental count is highly associated with the temperature of the region.
- The bike rentals were demanding in April to November months based on the month wise data.
- People tends to rent bikes during working days than holidays.
- If the weather is clear people will rent bikes more often.

Evaluation Parameters on model:
 - R-squared value = 0.843
 - Adj. R-squared = 0.839.
 - Duirng the validation coefficient of determination of the model is obtained as 0.8039 which means the model is 80.39% effenctive. 
 - mean square error is also minimum (0.0965) which indicates best fit of model.

The variables which are significant for predicting the bike rental count is as follows:
 - Weather: Cloudy, snow, temp, hum, windspeed
 - Month: Jan, Sept, Jul
 - Season: Summer, Winter
 - Calender: Year, Holiday, workingday.


**Equation for best fit line is**:
 
 Cnt = 0.2556 + 0.2289 * yr - 0.1127 * holiday - 0.0189 * workingday + 0.5703 * temp - 0.1708 * hum - 0.1935 * windspeed  + 0.0751 * Summer + 0.1267 * Winter - 0.0379 * Jan - 0.0473 * Jul + 0.0937 * Sept - 0.0543 * Cloudy - 0.2385 * Snow.
