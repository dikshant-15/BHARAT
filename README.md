# BHARAT INTERN 
# DIKSHANT SHARMA
## TASK 1 :  Stock Price Prediction : Take stock price of any company you want and predicts its price by using LSTM

## Introduction
This repository contains a stock price prediction project using the Long Short-Term Memory (LSTM) neural network. The goal of this project is to predict the stock price of any company by utilizing historical stock price data and employing an LSTM model. This project is a part of my internship, where I explore the fascinating field of time series forecasting using deep learning techniques.

## Dataset
The dataset used for this project includes historical stock price data for the "Google". It contains essential features such as Date, Open, High, Low, Close, Volume, and Adjusted Close. The dataset is structured as a time series, with chronological data points for each trading day. The historical stock price data will be divided into training and validation sets to train and evaluate the LSTM model.

## Requirements
To run the code and reproduce the predictions, you will need the following software and libraries:

Python (>= 3.6)
Jupyter Notebook (for running and visualizing the code)
Pandas (data manipulation)
Numpy (numerical operations)
Matplotlib (plotting)
Tensorflow (>= 2.0) (deep learning framework)
Keras (API for working with Tensorflow)

## Model Architecture
The LSTM model is a type of recurrent neural network that is well-suited for handling sequential data like time series. It consists of multiple LSTM layers followed by one or more fully connected (Dense) layers for the final prediction. The architecture and hyperparameters of the model can be adjusted based on the complexity of the dataset and the desired prediction accuracy.

## Evaluation
The performance of the LSTM model can be evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). Additionally, visualizing the predicted stock prices against the actual prices can provide valuable insights into the model's accuracy.
