# ML-Price_prediction_SMA

Machine Learning for price movement prediction using SMA indicators

Data for model training from CryptoDataDownload.com
Data for predictions obtained with cryptowatch-sdk
Model save and load with pickle library


How to use this notebook:

Create model

  * Create and train a new model: execute cells from 1 to 6. Can save the model to local computer or google drive on cell 7


Load model (instead of creating it again)

  * Load a pretrained model on cell 8. Execute first cells 1,2 and 4

Predictions

  * Execute Prediction Init(cell 9). Can be used recent price data from different exchanges or input a custom historic bar data

  * After the model was created or loaded and the prediction init cell was executed, Run the model prediction(cell 10) any times as needed. It can predict for a historic bar selected by shift toward current bar(0), or for a bar series starting from current to do backtesting.

** DISCLAIMER: The resources available on this project are purely and exclusively for educational purposes, and are not intended as, and shall not be understood or construed as, financial advice. I am not an attorney, accountant of financial advisor, nor am I holding myself out to be, and the information contained on this project are not a substitute for financial advice from a professional.
