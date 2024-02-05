Time Series Analysis and Stock Price Prediction with ARIMA
Overview
This Python script performs time series analysis and stock price prediction for Apple stock using the Autoregressive Integrated Moving Average (ARIMA) model. The script loads historical Apple stock price data from a CSV file, decomposes the time series into trend, seasonal, and residual components, fits an ARIMA model to the data, makes predictions, evaluates the model performance, and visualizes the results.

Requirements
Python 3.x
Required Python libraries:
numpy
pandas
matplotlib
statsmodels
scikit-learn
Usage
Ensure that you have Python installed on your system along with the required libraries mentioned above.
Place your Apple stock price data in a CSV file named data.csv. The CSV file should contain at least two columns: Date and Close representing the date and closing price of the stock, respectively.
Run the Python script stock_price_prediction.py.
Steps Performed in the Script
Load the Apple stock price data from data.csv and preprocess it.
Perform seasonal decomposition of the time series into trend, seasonal, and residual components using the multiplicative model.
Visualize the original time series along with its trend, seasonal, and residual components.
Split the data into training and test sets.
Fit an ARIMA model to the training data.
Make predictions using the ARIMA model on the test set.
Evaluate the performance of the ARIMA model using Mean Squared Error (MSE).
Visualize the actual vs. predicted stock prices.
