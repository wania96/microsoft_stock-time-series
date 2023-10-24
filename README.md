# microsoft_stock-time-series
# Microsoft Stock Data Analysis

This project focuses on analyzing Microsoft stock data and performing time series forecasting using various methods including Moving Averages (MA), Autoregressive Integrated Moving Average (ARIMA), and Seasonal ARIMA (SARIMA). Additionally, it provides a summary of Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE) values to evaluate the accuracy of these forecasting methods.

## Dataset

The dataset used in this project contains historical Microsoft stock prices over a specified time period. The data includes information about the opening, closing, high, and low prices, as well as trading volume.

## Methods

### Moving Averages (MA)

The Moving Averages method was used to create simple models for stock price prediction. This method smooths the data by taking an average over a certain number of past time points. In this project, different moving averages, such as the Simple Moving Average (SMA) and Exponential Moving Average (EMA), were explored and evaluated.

### Autoregressive Integrated Moving Average (ARIMA)

The ARIMA model is a widely used time series forecasting technique that takes into account autoregressive, differencing, and moving average components. This project applied the ARIMA model to predict Microsoft stock prices, and the model's accuracy was assessed using the evaluation metrics mentioned above.

### Seasonal ARIMA (SARIMA)

In some cases, time series data exhibits seasonality, which is a recurring pattern at regular intervals. The Seasonal ARIMA (SARIMA) model extends the ARIMA model to account for seasonality in the data. This project implemented SARIMA for Microsoft stock price prediction and evaluated its performance.

## Evaluation

The accuracy of the forecasting models (MA, ARIMA, SARIMA) was assessed using the following metrics:

- Mean Absolute Error (MAE): A measure of the average absolute errors between predicted and actual values.
- Mean Squared Error (MSE): An average of the squared differences between predicted and actual values.
- Root Mean Squared Error (RMSE): The square root of the MSE, giving an estimate of the spread of errors.
- Mean Absolute Percentage Error (MAPE): A percentage-based error metric that measures the average percentage difference between predicted and actual values.

## Results

The results of the analysis are as follows:

- **Moving Averages (MA)**: [MAE], [MSE], [RMSE], [MAPE]
- **Autoregressive Integrated Moving Average (ARIMA)**: [MAE], [MSE], [RMSE], [MAPE]
- **Seasonal ARIMA (SARIMA)**: [MAE], [MSE], [RMSE], [MAPE]

## Conclusion

This project provides insights into the application of different time series forecasting methods to predict Microsoft stock prices. By comparing the results of these models and their respective evaluation metrics, you can gain a better understanding of the accuracy and performance of each method in predicting stock prices.

For further details and code implementation, please refer to the project files.

