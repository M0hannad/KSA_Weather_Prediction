
# Temperature and Wind Speed Forecasting using Two Machine Learning Models
![image](https://user-images.githubusercontent.com/86031983/148937545-604c9533-5cce-4e21-a0a7-2bf310895dc2.png)

## Contents
- [Project Describtion](#project-describtion)
- [Dataset](#Dataset)
- [Programming Language](#Programming-Language)
- [Approach](#Approach)
- [Limitation](#Limitation)
- [Results and Evaluation](#Results-and-Evaluation)
- [Future work](#Future-work)

## Project Describtion

The idea of the project is to build machine learning model that able to forecast the weather elements in Saudi Arabia. The main goals this project are:

- Predict Temperature and Wind Speed for different cities in Saudi Arabia.

- Compare the results of using two ML models.

- Use the available data to understand how is the weather is changing in Saudi Arabia.


## Dataset

The dataset contains a 249023 rows and 15 columns, and these columns are:

|Variable | Describtion      |
| ------------- |:-------------| 
| City    | 13 major cities in Saudi Arabia |
| Date      | Record date in DD/MM/YY formats
| Time | Recored time in 24-Hour time format|
|Year|Recorded Year|
|Month|Recorded Month |
|Day| Recorded Day |
|Hour| Recorded Hour|
|Minute| Recorded Minute |
|Weather| Weather description ( Clear - Sunny - ... )|  
|Temperature| Rerorded temprature in °C| 
|Wind| wind speed measured in kph| 
|Humidity| Percentage of humidity|
|Barometer| Atmospheric pressure in  hPa|
|Visibility| How far an object van be seen (in km)|


## Programming Language
Python

## Approach:

Two machine learning models are used to for the predictive analysis:
- `Linear Regression`
- `Random Forest`

## Limitation:
- Limited Data Available.
- Not using time series analysis for forecasting.
- Few models were used.


## Results and Evaluation:
MAE (Mean absolute error), and R-squared are used to evaulate model accuracy.

**Temperature Using Linear Regression:**

> Accuracy for Linear Regression: 0.7785913886229557

**Temperature Using Random Forest:**

> Accuracy for Random Forest: 0.9803790198725455

**Wind Spead Using Random Forest:**
> Accuracy for Wind Speed: 0.5938123950492595



## Future work:
- Include more cities
- Use analysis information to help estimate the potential for solar and wind energy in Saudi Arabia.
- Forecasting of the rainfall as well.
- Make the prediction using Time Series Analysis.


## Conclusion:
The data for the KSA weather was obtained and utilized to perform predictive machine that can forecast the temprature and wind speed. A Exploratory Data Analysis were carried out to find the trending weather behaviour in Saudi Arabia. Although a relativly good accureacy were achived, this model is not so reliable as the sample size were not big enough (only 3 years time range). Two machine learning models were train, tested, then compared to find the optimal one. To evaluate the model accuracy, several evaluation metrics were used for comparison (MAE, MSE, and R^2). The Mean absolute error for random forest model was 0.17 which is better than 0.37 in the linear regression model.
