
# Temperature and Wind Speed Forecasting using Two Machine Learning Models
![image](https://user-images.githubusercontent.com/86031983/148937545-604c9533-5cce-4e21-a0a7-2bf310895dc2.png)

## Contents
- [Project Describtion](#project-describtion)
- [Dataset](#Dataset)
- [Language and Libraries](#Programming-Language-and-libraries)
- [Approach](#Approach)
- [Limitation](#Limitation)
- [Results and Evaluation](#Results-and-Evaluation)
- [Future work](#Future-work)
- [Conclusion](#Conclusion)

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
|Weather| Describtion of weather condition ( Clear - Sunny - Cloudy - ... )|  
|Temperature| Rerorded temprature (in °C)| 
|Wind| wind speed measured (in kph)| 
|Humidity| Percentage of humidity|
|Barometer| Atmospheric pressure (in hPa)|
|Visibility| a measure of the distance at which an object or light can be clearly discerned (in km)|


## Programming Language and Libraries
**Python**:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn


## Approach:

Two machine learning models are used to for the predictive analysis:
- **Linear Regression**
- **Random Forest**

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

**Wind Speed Using Random Forest:**
> Accuracy for Wind Speed: 0.5938123950492595



## Future work:
- Include more cities
- Use analysis information to help estimate the potential for solar and wind energy in Saudi Arabia.
- Forecast the rainfall as well.
- Make the prediction using Time Series Analysis.


## Conclusion:
The data for the Saudi Arabia Weather History was obtained and utilized to perform predictive machine that can forecast the temprature and wind speed. An Exploratory Data Analysis were carried out to find the trending weather behaviour in Saudi Arabia. Although a relativly good accureacy were achived, this model is not so reliable as the sample size were not big enough (only 3 years time range). Two machine learning models were trained, tested, then compared to find the optimal model. To evaluate the model accuracy, several evaluation metrics were used for comparison (MAE, MSE, and R^2). The R2 for random forest model was 0.98 which is better than 0.78 in the linear regression model.
