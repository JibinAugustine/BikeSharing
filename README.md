# Bike Sharing Demand Prediction
> This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- Understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market
- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions

We first did an EDA and then built a linear regression based on EDA model and then used RFE for feature selection and then combined both to get the final model
The top factors include temperature(higher the temperature more the demand), weather (In sunny or cloudy weather more users present) and season(During the fall season many use bikes). 

Based on this we created a linear model which predicts the demand of bikes with an adjusted R-score of 0.81 with the test dataset


## Technologies Used
- pandas 
- statsmodel
- sklearn


## Contact
Created by [@JibinAugustine] - feel free to contact me!
