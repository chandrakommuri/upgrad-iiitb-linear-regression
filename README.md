# Linear Regression Assignment - Bike Sharing System
> This is a programming assignment where in we have to build a multiple linear regression model for the prediction of demand for shared bikes. A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
BoomBikes, a US-based bike-sharing provider, is experiencing a significant downturn in revenue due to the COVID-19 pandemic. In response, the company is preparing a strategic business plan to boost revenue post-lockdown by gaining a deeper understanding of the demand for shared bikes. The company aims to understand the demand for shared bikes once restrictions are lifted. They have engaged a consulting firm to identify significant variables that influence bike demand in the American market, using a dataset with factors including meteorological conditions and user trends. The goal is to optimize service offerings and maximize profits by effectively responding to the anticipated increase in demand.

#### Business Goals:

- To identify the variables that significantly predict and explain bike-sharing demand.

- To efficiently meet customer needs and enhance profitability as the market recovers.

- To create a linear model that analyzes various factors affecting bike demand in the American market.

- To know the accuracy of the model, i.e. how well these variables can predict house prices.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- R2 Score of train data: 80%
- R2 Score of test data: 77%
- R2 Scores of train and test data are comparable
- This indicates that the model is decent
- Equation of the best fitted line: $ cnt = 0.088 + 0.568 \times temp + 0.233 \times y2019 + 0.126 \times winter + 0.089 \times Sep + 0.081 \times summer - 0.087 \times holiday - 0.145 \times windspeed - 0.253 \times light\_snow\_rain $

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas 2.2.2
- matplotlib 3.9.2
- seaborn 0.13.2
- statsmodels 0.14.2
- sklearn 1.5.0

## Acknowledgements
Give credit here.
- This project was inspired by live session on ML by IIITB
- UpGrad course on ML & AI


## Contact
Created by [@chandrakommuri] - feel free to contact me!