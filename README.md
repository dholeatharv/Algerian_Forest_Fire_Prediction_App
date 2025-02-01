# Algerian_Forest_Fire_Prediction_App

### This project aims to predict the likelihood of forest fires in Algeria using machine learning techniques based on weather and environmental data.

## Introduction
Forest fires pose a significant threat to ecosystems, property, and human life. Accurate prediction of forest fires can aid in preventive measures and resource allocation. This project utilizes machine learning models to predict the Fire Weather Index (FWI), which indicates the potential for fire activity based on various environmental factors.

## Dataset
The dataset used in this project is the Algerian Forest Fires Dataset from the UCI Machine Learning Repository. It contains forest fire observations from two regions in Algeria: the Bejaia region and the Sidi Bel-Abbes region, collected between June 2012 and September 2012.

## Attributes:
Temperature (°C)
Relative Humidity (%)
Wind Speed (km/h)
Rainfall (mm)
Fine Fuel Moisture Code (FFMC)
Duff Moisture Code (DMC)
Initial Spread Index (ISI)
Classes (Fire/Not Fire)
Region

## Features
#### Data Cleaning and Preprocessing: Handling missing values, encoding categorical variables, and normalizing numerical features.
#### Exploratory Data Analysis (EDA): Visualizing data distributions and relationships between variables.
#### Modeling: Training regression models to predict the Fire Weather Index (FWI).
#### Web Application: A user-friendly interface to input environmental parameters and receive FWI predictions.

## Modeling
Various regression models were explored, including:
Linear Regression
Ridge Regression
Lasso Regression
ElasticNet

## Application
A Flask web application was developed to provide an interactive platform for users to input environmental parameters and receive FWI predictions. The app is deployed on Heroku for accessibility.

## Results
The Ridge Regression model achieved the lowest error rates among the tested models, indicating its effectiveness in predicting the Fire Weather Index based on the provided environmental parameters.

![image](https://github.com/user-attachments/assets/a7a97b06-8f20-4d19-b220-e3ee9072e301)
