# MSDS696_X70_Data-Science-Practicum-II

## CRIME DATA ANALYSIS-LOS ANGELES

![LA](https://user-images.githubusercontent.com/109038700/206540424-f08b1f3d-c7d2-4ad4-b768-d1594af751e6.jpeg)

### Regis University

### Author: Sangita Lamichhane

### Table of contents 

**1. Project Description**

  A. Project Introduction
  
The year of 2020 had a historic rise of demonstrations across the United States calling to 'Defund the Police.' The funding trend of increasing police spending was reversed for the first time in years by reducing the Los Angeles Police Department (LAPD) budget by $150 million.

This project analyses the available crime data by simple exploratory data analysis and using Machine learning to predict the crimes that occur in Los Angeles.

![Screen Shot 2022-12-08 at 11 45 48 AM](https://user-images.githubusercontent.com/109038700/206540968-cf823fb5-24dd-4e0b-b59f-95f1a864b12a.png)

  B. Problem Statement
  
Los Angeles police department is one of the largest in the country, with jurisdiction of around 4 million people. Through this project we aim to identify which areas and populations in LA have been hit the hardest by crime in past few years. Furthermore, this project studied the following business problem from the data:

1. Areas in LA with highest reported crime.

2. Top impacted demographics in LA.

3. Crime changes during the time period of study


**2. Data Collection**

The crime data  Los Angles Crime data  for this project is taken from the city of Los Angeles website.
The data reflects incidents of crime in the City of Los Angeles from 2010 to 2022.


**3. Generic Flow Of Project**

A. Data cleaning 

B. Data Exploration and Visualizations

C. Model Approach and development

D. Model Validation and comparision

E. Predictions

**4. EDA**

We collected the datas and performed data cleaning. We check if there are any missig values and worked on those missing values as well as changing date format.    

![Screen Shot 2022-12-08 at 3 38 02 PM](https://user-images.githubusercontent.com/109038700/206582058-31e0156c-f6a2-4a92-990b-0ab4739ead5d.png)



**5. Model Approach**

For the analysis, we have done simple EDA based approach to answer the business questions as well as used time series ARIMA model for predicting the crime. Univariate time series modeling is used to forecast reported crime in Los Angeles to determine crime trends in LA. Working with AR, MA, ARMA, and SARIMA models we determined the best fit with the lowest AIC score. Then evaluated our best model, a SARIMA model, using RMSE and AIC. The final model had an RMSE 51.8 with AIC 722.89.

![image](https://user-images.githubusercontent.com/109038700/207454310-6a024517-efd8-4ec5-9a7f-8804195ac197.png)


**6. Conclusion**
From our explorative data analysis, our model predicted a slight decrease in crime rate from 2017 onwards. The funding for LAPD should be redistributed to social service solutions to public safety problems in the high crime areas such as 77th Street, Southwest, and Pacific. 
 
We can see the top vulnerable communities in LA is Black and Latina communities. The highest crime area seems to be 77th street and Southwest in LA. White community seems to be least vulnerable but one of the reasons could be there are less white population compared to others in those area.
 
Year 2017 saw the highest average number of crimes reported, while 2013 saw the lowest average number of crimes reported in LA. Additionally, we can see decreasing trend of average crime from 2017 onwards.

 
**7. Limitation and Future Considerations**

Gathering more historical data could help make stronger predictions and forecasts further into the future.
Furthermore, including exogenous variables from census data to add complexity to the univariate model will be insightful. Can implement a Facebook Prophet model for comparision and model evaluation.
Additionally, use incoming data to evaluate our model's forecasting performance.

**Data sources:**

https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z 

https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

Note: I could not attach the data files and clean dataset being so huge in size.
