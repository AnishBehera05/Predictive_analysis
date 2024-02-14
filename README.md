**README**

**Stock Price Prediction Using Time Series Forecasting Models**

This repository contains implementations of various time series forecasting models applied to predict Apple stock prices. The models include:

1. Autoregressive Integrated Moving Average (ARIMA)
2. Convolutional Neural Network (CNN)
3. Long Short-Term Memory (LSTM)
4. Support Vector Regression (SVR)

**Dataset:**
The dataset used in this project is provided in the `data.csv` file. It includes historical Apple stock prices with date-time information.

**Dependencies:**
To run the code in this repository, you need the following dependencies:

- Python 3.x
- NumPy
- pandas
- Matplotlib
- scikit-learn
- TensorFlow (for CNN and LSTM models)
- Keras (for CNN and LSTM models)
- Statsmodels (for ARIMA model)

You can install the required dependencies using pip:

```
pip install -r requirements.txt
```

**Usage:**
- Each model implementation is provided in a separate Python script.
- Run each script to train and evaluate the corresponding model.
- The evaluation includes the Mean Squared Error (MSE) metric to assess prediction accuracy.

**How to Run:**
1. Clone this repository to your local machine:

```
git clone https://github.com/yourusername/stock-price-prediction.git
```

2. Navigate to the cloned directory:

```
cd stock-price-prediction
```

3. Run the desired model script:

```
python arima_model.py
python cnn_model.py
python lstm_model.py
python svr_model.py
```

**Contributing:**
Contributions to this repository are welcome. If you have any suggestions, improvements, or additional models to add, feel free to submit a pull request.

**License:**
This project is licensed under the MIT License. Feel free to use and modify the code for your own purposes.

**Acknowledgments:**
The implementations in this repository are based on various tutorials, documentation, and research papers on time series forecasting and machine learning. Special thanks to the authors and contributors of these resources.

**Disclaimer:**
This project is for educational and research purposes only. Stock price prediction is inherently uncertain and should not be used as the sole basis for investment decisions. Always consult with a financial advisor before making investment choices.
