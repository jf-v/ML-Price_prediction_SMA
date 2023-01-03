# Machine Learning for price movement prediction using SMA indicators

## **Resources**

* Prices data for model training obtained from [CryptoDataDownload](https://www.cryptodatadownload.com/): provides a larger amount of historical bars to train the model, but there are only two timeframes available, 1 hour or 1 day.
* Prices data for predictions obtained with [cryptowatch-sdk](https://github.com/cryptowatch/cw-sdk-python): limited to 1000 historical bars, but it provides larger amount of timeframes for backtesting
* Save and load models with pickle library

## **Objetive**

* Create and train a machine learning model, then use it
to get price movement predictions for a certain amount of bars towards future. The predictions will estimate the probabilities of the price to be above or below the current price after a certain amount of time, defined by the shift bars and timeframe of the price data. Example: a prediction target shift of 7 bars on a 1 hour timeframe will be the price expected position (up or down) after 7 hours

## **Fast Execution**

* **Run all cells** except 6 and 7, using the default inputs

## **Create model**

* Create and train a new model: execute cells from 1 to 5. Can save the model to local computer or google drive on cell 6

## **Load model (instead of creating it again)**

* Load a pretrained model on cell 7. Execute first cells 1,2 and 4

## **Predictions**

* Execute **Prediction Init**(cell 8). Can be used recent price data from different exchanges or input a custom historic bar data

* With the model already created or loaded and the prediction init cell executed, **run the model prediction**(cell 9) any times as needed. It can predict for bar series starting from current bar or for a historic bar selected by shift toward current bar index(0)

### **DISCLAIMER**: The resources available on this project are purely and exclusively for educational purposes, and are not intended as, and shall not be understood or construed as, financial advice.
