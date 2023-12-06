# Machine Learning -Time Series
Sales data prediction using SARIMAX model

## Problem Description
The problem is to predict the number of monthly sales of champagne for the Perrin Freres label (named for a region in France).

The dataset provides the number of monthly sales of champagne from January 1964 to September 1972, or just under 10 years of data.

The values are a count of millions of sales and there are 105 observations.

The dataset is credited to Makridakis and Wheelwright, 1989.

## Methodology
* Data loading, clean up, indexing, getting data ready for visualisation.
* As the data was not stationary(inferred from visualisation), differencing was used to make it stationary.
* Also as the data was seasonal, seasonal differencing was done to make data non seasonal.
* ARIMA model was used on raw data to show how wrong the predictions can go if the data is not stationary or seasonality is not removed.
* Sarimax model was used on cleaned data.
* Prediction on current data was used to check the accuracy, and the prediction was reasonably accurate. Future predictions were also tried.


## Code and Resources Used
* SciPy
* NumPy
* Matplotlib
* Pandas
* scikit-learn
* statsmodels

## Code and Resources Used
* SciPy
* NumPy
* Matplotlib
* Pandas
* scikit-learn
* statsmodels


