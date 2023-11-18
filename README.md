# Demand Prediction for Shared Bikes

> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
> BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19
> They want to understand the factors affecting the demand for these shared bikes in the American market
> Which variables are significant in predicting the demand for shared bikes ?
> How well those variables describe the bike demands ?
> You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.

## Table of Contents

- [General Info](#general-information)
- [Techniques Used](#techniques-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Machine learning models can be classified into the following three types based on the task performed and the nature of the output:
- Regression: The output variable to be predicted is a continuous variable, e.g. in this case demand for shared bikes
- Classification: The output variable to be predicted is a categorical variable
- Clustering: No pre-defined notion of a label is allocated to groups/clusters formed

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

> Which variables are significant in predicting the demand for shared bikes & How well those variables describe the bike demands.
- Variables positively impacting the demand of shared bikes ranked by how well they describe the bike demand : temp, yr, season_winter, mnth_Sep, season_summer
- Variables negatively impacting the demand of shared bikes ranked by how well they describe the bike demand : mnth_Jul, season_spring, weathersit_Misty, holiday, windspeed, weathersit_Light

> Variables increasing bike demand
- temp is the most significant factor for increase in bike demand. As the temperature increases the demand for shared bikes increases.
- temp is followed by yr to positively impact the bike demand. As the years pass by the demand for shared bikes is increasing.
- There is more demand of shared bikes in winter season and September month 
- Summer season also has increase in demand for shared bikes

> Variables decreasing bike demand
- windspeed is the most significant factor for decrease in bike demand followed by weathersit_Light. With the increase in windspeed there will be decrese in shared bikes demand. Also in the Light Snow, Light Rain, Thunderstorm the bike demand will be low.
- Bike demand decreses in misty cloudy wheather and on holidays
- Bike demad will be less in spring season and in july month

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Techniques Used

As our problem aligns with Linear Regression, we will performed following steps to build the model
- Reading and Understanding the Data
- Data Cleaning & Preparation
- Visualizing the data to check if the Linear Regression can be applied
- Creating dummy variables
- Splitting the Data into Training and Testing Sets
- Training Data Preprocessing
- Modeling on training Data
- Residual analysis on Train data
- Model Predictions on Test Data
- Model Evaluation

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@nikitapatil1122] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># LendingClubCaseStudy
