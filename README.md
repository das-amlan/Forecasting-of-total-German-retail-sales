# Forecasting of Total German Retail Sales
This repository contains an R code that performs time-series forecasting of total German retail sales. The code uses an `ARIMA` model to forecast the sales and evaluate its accuracy.

## Steps
1. Load the required libraries such as "ggplot2", "forecast", "readxl".

1. Read the data from a `.csv` file using the `read_csv()` function from the `readr` library.

1. Convert the date column in the data to a time series format using the `ts()` function.

1. Plot the time series data using `ggplot()` and `geom_line()`.

1. Decompose the time series into its components (trend, seasonality, and residuals).

1. Fit an ARIMA model to the data using the `auto.arima()` function and then perform forecasting using the `forecast()` function.

1. Plot the forecasted values along with the original data using `autoplot()`.

1. Evaluate the accuracy of the forecast using the `accuracy()` function and calculate various performance metrics such as Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and Mean Squared Error (MSE).

1. Plot the residuals of the forecast using `autoplot()` to check for any patterns.

1. Finally, the code saves the forecasted values to a `.csv` file using the `write_csv()` function.

## How to run the code
* Clone the repository to your local machine.
* Open the `Test.R` file in R Studio.
* Set the working directory to the location of the code file and data file.
* Run the code line by line or use the source() function to run the entire code.
## Data
The data used in the code is a `.csv` file containing the total German retail sales from January 2000 to December 2022.

## Contributions
Contributions are welcome! If you want to contribute to this project, please fork the repository and create a pull request with your changes.
