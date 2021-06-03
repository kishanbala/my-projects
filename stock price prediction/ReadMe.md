![prediction_accuracy](https://user-images.githubusercontent.com/44191470/120594668-ed2c3780-c45e-11eb-8e78-3f860ed37301.PNG)
# Predict stock market prices
The aim of this project is to predict the closing price of a stock listed in the NSE based on the Open price for a given day. The project is purely regression based and I have handled ensemble technique to demonstrate the effectiveness of ensemble models. 
Totally 3 models are used:
1. Ensemble method(Linear + AdaBoost +XGBoost Regressor)
2. RandomForeset Regressor
3. A simple LSTM.

The results showed that ensemble did not support our use case whereas randomforeset and LSTM were most effective. 
I have tried to use matplotlib library to visualize the performance of each model.
