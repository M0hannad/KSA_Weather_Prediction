
# Temperature and Wind Speed Forecasting using Two Machine Learning Models

## Project Describtion

The idea of the project is to build machine learning model that able to forcast the weather elements in Saudi Arabia. The main goals for this project are:

- Predict temperature and Wind Speed for different cities in Saudi Arabia.

- Compare the results for using two ML models.

- Use the available data to understand how is the weather is changing in Saudi Arabia.


## Dataset

The dataset contains a 249023 rows and 15 columns, and these columns are:

| Variable | Describtion      |
| ------------- |:-------------| 
| City    | 13 major cities in Saudi Arabia |
| Date      | Record date in DD/MM/YY formats
| Time | Recored time in 24-Hour time format|
|Year||
|Month| |
|Day|  |
|Hour| |
|Minute|  |
|Weather| Weather description ( clear - sunny - .... )|  
|Temperature| Rerorded temprature in °C| 
|Wind| wind speed measured in kph| 
|Humidity| Percentage of humidity|
|Barometer| Atmospheric pressure in  hPa|
|Visibility| How far an object van be seen (in km)|


## Programming Laguage
Python

## Approach:
The steps taken to answer the research question listed above.

Sentiment Analysis
Topic Modeling

## Limitation:
- Limited Data Available.
- Not using time series focasting
- Finding the best model to use.
## Future work:
- Include more cities
- Use the information to help estimate the potential for solar and wind energy in Saudi Arabia.
- Prediction for the rainfall as well.
- Using Time Series Analysis.


## Results:
MAE (Mean absolute error), and R-squared are used to Evaulate the model accuracy.
- Using Lineaar Regression:

![image](https://user-images.githubusercontent.com/86031983/148729592-0b21ef80-de7f-4798-8850-c04f8541814e.png)

- Using Random forest:

![image](https://user-images.githubusercontent.com/86031983/148729628-daa2a906-a45c-4e31-8ec8-c26e77edc907.png)


### Conclusion:
The data for the KSA weather was obtained and utilized to perform predictive machine that can forcast the temprature and wind speed. A Exploratory Data Analysis were carried out to find the trening weather behaviour in Saudi Arabia. Although a relativly good accureacy were achived, this model is not so reliable as the sample size were not big enough (only 3 years time range).For a variety of There were several hurdles throughout the development process, particularly in the and model training stages. The accuracy of the model is 67 percent, indicating that it did not generalize effectively.
### References
