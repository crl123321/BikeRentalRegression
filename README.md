Here's a detailed breakdown of the Project:

Understanding the Data:

Get a concise summary of the data structure, which includes 731 rows and four numeric columns.
Obtain summary statistics (mean, min, max, standard deviation) for the dataset.

Exploring Relationships:

Create scatter plots to visualize relationships:
Temperature vs. Rentals: Positive linear relationship (as temperature increases, rentals increase).
Humidity vs. Rentals: Negative linear relationship (as humidity increases, rentals decrease).
Wind Speed vs. Rentals: Negative linear relationship (as wind speed increases, rentals decrease).


Splitting the Data:

Separate the dependent variable (rentals) into a DataFrame Y.
Separate the independent variables (temperature, humidity, wind speed) into a DataFrame X.
Use train_test_split from sklearn.model_selection to split X and Y into training and test sets (X_train, X_test, Y_train, Y_test).

Building the Model:

Import the LinearRegression class from sklearn.linear_model.
Create a linear regression model and fit it using X_train and Y_train.

Model Parameters:

Obtain the intercept value (3800.68).
Obtain the slope values (coefficients) for the predictors:
Temperature: 80.35
Humidity: -4665.74
Wind Speed: -196.22


Evaluating the Model:

Calculate the coefficient of determination (R²) using the score method, which is 98.2%, indicating a very good fit.
Calculate the mean absolute error (MAE) using mean_absolute_error from sklearn.metrics, which is ±194 bikes, indicating the average prediction error.
