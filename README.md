# Regression_Project:Bike_Sharing_Demand_Prediction
Now-a-days to increase the mobility comfort, the rental bikes (like Rapido, Ola bikes etc) are introduced in the urban cities. It is important to make the rental bike avaliable and accessible to public at the right time to lessen the waiting time. Bikes are more comfortable than cars in narrow lane areas. Eventually providing the city with a stable supply of rental bikes becomes a major concern. The climatic conditions effect the rental bike rides. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. In this project, different regression techniques are applied on the bike sharing data. There are 14 columns in the dataset. Fields Description:
Date - Date,
Hour - Hour of the day (0-23),
Temperature - Temperature of the day,
Humidity - Humidity measure,
Windspeed - Windspeed,
Visibility - Visibility measure,
Dew Point Temperature - Dew Point Temperature Measure,
Solar Radiation - Solar Radiation Measure,
Rainfall - Rainfall in mm,
Snowfall - Snowfall measure,
Seasons - 1= spring, 2 = summer, 3 = fall, 4 = winter,
Holiday - Whether a holiday or not,
Functional Day - Whether a functional day or not.
Firstly the data is cleaned. Secondly, EDA analysis is done to find which factors effect the rental bike count. After that, in order to make the data ready for machine learning, skewness is verified and transformation is applied everywhere needed to make the data normally distributed. Outliers are found and removed if needed. If these treatments are not applied it results in wrong predictions. The data is scaled equally over all the columns using the different scaling techniques like Standard Scalar, MinmaxScalar etc. Now data is splitted into train and test data with certain ratio and random state. The data is modelled using train data and prediction is done on test data. The different evaluation metrics are applied to check the accuracy of the model and results are compared to find the best model for this bike sharing demand dataset.
