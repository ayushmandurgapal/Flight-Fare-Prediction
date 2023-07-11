# Flight Fare Prediction

<img src="Images/used_cars.jpg">

### Overview

This is a regression model that can be used to predict the price of flights based on certain input parameters like departure date, departure time, arrival time, source city, destination city, number of stops, and the airline. This regression model is effective in giving cheapest flight options to customers.

### Data
The dataset has been downloaded from Kaggle and consists of data for domestic flights within India and for the year 2019. Hence, the model developed is valid for Indian cities and Indian airline companies. 

### Modelling

After cleaning and preprocessing the data to make it fit to feed the model, a **RandomForest model** was created. This was found as the best modelling technique after considering other regression techniques like multiple linear regression, support vector machines, decision trees, etc.
Hyperparameter tuning using **RandomizedSearchCV** has also been used to fine tune the model for better predictions.

The final model has low Root Mean Squared Error and Mean Absolute Error, showing that it is a robust model for predictions.

