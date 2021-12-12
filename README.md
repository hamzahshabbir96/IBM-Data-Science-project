# IBM-Data-Science-project
Prediction analysis of SpaceX by creating and optimizing different machine learning algorithm on IBM Watson cloud using SpaceX API and presented reports in the form of interactive dashboard and visual analytics 

## Outline 
- [Executive Summary](#Executive-Summary)
- [Introduction](#Introduction)
- [Methodology](#Methodology)
- [Results](#Results)
- [Conclusion](#Conclusion)
- [Appendix](#Appendix)


## Executive Summary
- Data for this were collected from SpeceX API and Wikipedia page of SpaceX. Data were sampled for classification whether landing was successful or not. Exploratory analysis were done using SQL. For detailed analysis visualization were done in folium map and dashboards.
- Prediction analysis were done on four machine learning algorithm to select best accurate model by hyper tuning model using grid search. 
Models:
  - Logistic Regression
  - Support Vector  Machine
  - Decision Tree Classifier
  - K Nearest Neighbors
- Accuracy of all models were between 80 % to 85 % which can be considered good.
## Introduction
Background
- With the commercialization of space, there is going to be huge competition in space market considering investment, pricing and strategy
- Possible due to ability to recover part of rocket from stage I
- Hypothetical space company analysis to present scenario to compete with SpaceX
Problem
- Prediction of successful stage I recovery by training model on machine learning classification algorithm
## Methodology
- Data collection methodology:
  - Integration of data from SpaceX API and data collected from scrapping wikipedia
- Perform data wrangling
  - Classifying successful landing as successful and other as unsuccessful
- Perform exploratory data analysis (EDA) using visualization and SQL
- Perform interactive visual analytics using Folium and Plotly Dash
- Perform predictive analysis using classification models
- Hyper parameters of model were tuned using grid search
## Data Collection
- Data were extracted using two method and sources:
  - Extracted from SpaceX API and then conversion of result from json to dataframe using pandas
  - Web scrapping was done to extract data from Wikipedia page of SpaecX using request and beautifulsoup library in python
- SpaceX API Data columns
FlightNumber, Date, BoosterVersion, PayloadMass, Orbit, LaunchSite, Outcome, Flights, GridFins, Reused, Legs, LandingPad, Block, ReusedCount, Serial, Longitude, Latitude
- Wikipedia Data columns
Flight No., Launch site, Payload, PayloadMass, Orbit, Customer, Launch outcome, Version  Booster, Booster landing, Date, Time

## Data collection Space-X API
Data collection approach (API)

![image](images/dc1.PNG)

Data collection approach Web scraping

![image](images/dc2.PNG)
