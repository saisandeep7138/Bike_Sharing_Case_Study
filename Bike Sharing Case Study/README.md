# Bike Sharing Demand Prediction
A comprehensive analysis of bike sharing demand using Linear Regression to help BoomBikes optimize their post-pandemic business strategy.

## Table of Contents
1.General Information
2.Business Problem
3.Dataset Overview
4.Technologies Used
5.Methodology
6.Key Findings
7.Recommendations
8.Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project is part of the Executive PG Diploma program from UpGrad in collaboration with IIIT Bangalore. The study applies Predictive Analytics and Linear Regression techniques to analyze bike sharing patterns and predict future demand.

## Business Problem
BoomBikes, a US bike-sharing provider, has faced significant revenue decline during the COVID-19 pandemic. The company aims to:

Understand post-pandemic bike sharing demand patterns
Identify key variables influencing revenue
Develop an accurate demand prediction model
Create a strategic business plan for post-pandemic recovery


## Dataset Overview
The analysis uses a comprehensive dataset containing bike sharing data with various features including:

Temporal information (months, seasons)
Weather conditions
Temperature
User patterns
Historical demand data
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1.Model Fit:
->The model has a strong predictive power with an R-squared of 0.823, meaning it explains 82.3% of the variance in bike sharing demand (cnt)

->The adjusted R-squared of 0.819 is very close to the R-squared, suggesting the model isn't overfitted

->The F-statistic is very high (210.8) with a highly significant p-value (2.22e-179), indicating the model is statistically valid

2.Key Variable Effects:

->Temperature (temp) has the strongest positive effect (coefficient = 0.5281) and is highly significant (p < 0.001)

->Year (yr) shows a positive trend (0.2286) indicating increasing demand over time

->Humidity (hum) and windspeed have significant negative effects (-0.2455 and -0.2036 respectively)

->Holidays show a slight negative effect (-0.0599)

->Weekdays have a small positive effect (0.0071)

3.Practical Implications:

-> Weather conditions (temperature, humidity, windspeed) are crucial factors affecting demand

-> There's a clear growth trend over years

-> Day type (holiday vs. weekday) has a measurable impact on usage patterns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python for Data Science
MS Excel
Required Python libraries:
    NumPy
    Pandas
    Matplotlib
    Seaborn
    Scikit-learn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

-> Project developed as part of UpGrad & IIIT Bangalore Executive PG Diploma program

-> Original dataset and problem statement provided by BoomBikes


## Contact
Created by [@saisandeep7138] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->