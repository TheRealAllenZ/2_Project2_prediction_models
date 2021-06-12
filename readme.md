# Predicting 2015 Flight Delays 


## Overview

Every year, airline flights get delayed, costing travelers time and money. Many factors affect flight delays, including air traffic control backups, equipment delays, and weather. Our goal was to leverage the massive amount of data available on flight punctuality and weather to forecast whether a flight would be delayed. The project is based on the 2015 Flight Delay and Cancellation dataset from Kaggle ([click here to download](https://www.kaggle.com/usdot/flight-delays)). Unfortunately, due to time constraints, the weather data fetched using NOAA API was not used. Potentially Airlines could use these models to compute their flight delays.

### Data
The dataset contained data for airports, airlines, and flights. The Airports did not contain addresses. The flights data had some airports as 4 digit codes, 

### Scope
![Scope](Scope.png)

First a dataset was selected, with being cognizant of its usability, with enough features and significant data size. Then came the cleaning portion and data exploration. Followed by the modeling and visualization to show the results of the model. Finally, conclude which models were the best at predicting the delay.

An Exploratory Data Analysis was performed. The results of which fed into the feature selection process and then the feature encoding process.
Supervised and Deep learning models were used to predict the delay.

A two-fold approach was taken. The first was to predict the delay as 'short delay,' 'medium delay,' and 'long delay' (Classification). The other was to predict the delay itself (Regression).

### Multi-Class Classification

The Models used for predicting delays were as follows:

1. Random Forest
2. Decision Tree
3. K Nearest Neighbor
4. Gradient Boosting
5. Stochastic Gradient Descent 
6. Shallow NN & Deep NN (2 layers)

Conclusion:

The 2-layer Neural network outperformed all the supervised learning Models. The worst was the kNN, which returned terrible results.

## 






