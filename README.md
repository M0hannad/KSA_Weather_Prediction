
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

The idea of the project is to build machine learning model that able to forcast the weather elements in Saudi Arabia. The main goals for this project are:

- Predict temperature and Wind Speed for different cities in Saudi Arabia.

- Compare the results for using two ML models.

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
|Weather| Weather description ( clear - sunny - ... )|  
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
- Not using time series forcasting
- Finding the best model to use.


## Results and Evaluation:
MAE (Mean absolute error), and R-squared are used to evaulate model accuracy.
 >Using Lineaar Regression:

![image](https://user-images.githubusercontent.com/86031983/148729592-0b21ef80-de7f-4798-8850-c04f8541814e.png)

 >Using Random Forest:

![image](https://user-images.githubusercontent.com/86031983/148729628-daa2a906-a45c-4e31-8ec8-c26e77edc907.png)

## Future work:
- Include more cities
- Use the information to help estimate the potential for solar and wind energy in Saudi Arabia.
- Forecasting of the rainfall as well.
- Make the prediction using Time Series Analysis.


### Conclusion:
The data for the KSA weather was obtained and utilized to perform predictive machine that can forcast the temprature and wind speed. A Exploratory Data Analysis were carried out to find the trending weather behaviour in Saudi Arabia. Although a relativly good accureacy were achived, this model is not so reliable as the sample size were not big enough (only 3 years time range). For a variety of There were several hurdles throughout the development process, particularly in the and model training stages. The accuracy of the model is 67 percent, indicating that it did not generalize effectively.


