# House-Price-Prediction
This project is about the House Price Prediction

In this project the dataset is used in built [housing = fetch_california_housing()]
or you can get from Kaggle too.

I've used housing = fetch_california_housing()
First the dataset is readed 
Then the Target label is fixed or created
Using the function isnull 
It Detect missing values for an array-like object. This function takes a scalar or array-like object and indicates whether values are missing ( NaN in numeric arrays, None or NaN in object arrays, NaT in datetimelike).
Then finding the Correlation between the various features in the dataset
While finding the correlation you can correlate with the help of the HEAT MAP

SPLITING THE DATA INTO THE TRAINING AND TESTING DATA
Model is Training with the help of XGBoost Regressor
After training and testing the data , Finally the output can be displayed as Graphical representation.
