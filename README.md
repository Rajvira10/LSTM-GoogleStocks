# LSTM Stock Price Forecasting with Google (GOOGL) Stock Data

![image](https://github.com/Rajvira10/LSTM-GoogleStocks/assets/72084907/e1dd9287-3b59-40a9-ae7f-0adde84b927d)

## Overview

This project is an LSTM (Long Short-Term Memory) based stock price forecasting model built to predict the future price trends of Google (GOOGL) stock using historical price data from 2010 to 2023.

## Description

In this project, I utilized the power of recurrent neural networks, specifically Long Short-Term Memory networks, to capture and learn temporal patterns in the Google stock price data. The LSTM model was trained on historical stock price data to predict the future price movements.

The key steps involved in this project include:

1. Data Collection: I obtained historical stock price data for Google (GOOGL) from 2010 to 2022 using a financial data API.

2. Data Preprocessing: I cleaned and prepared the data for training the LSTM model. The data was scaled to facilitate training and to avoid numerical instability.

3. LSTM Model: I implemented an LSTM model using PyTorch. The LSTM network was designed to take previous 7 days of stock price sequences as input and predict the next day's closing price.

4. Training: The LSTM model was trained using the prepared data. The model was optimized using appropriate loss functions and evaluation metrics.

5. Forecasting: After successful training, I used the LSTM model to predict future stock price trends beyond the training period.

## Results

The LSTM model achieved promising results in forecasting the Google stock price. It demonstrated the ability to capture short-term and long-term trends in the stock price data, making it a valuable tool for potential investors and traders to make informed decisions.

I have visualized the actual vs. predicted stock price trends and included them in the project to showcase the model's performance.

## Future Improvements

While the LSTM model achieved satisfactory results, there are several areas for improvement:

- **Hyperparameter Tuning**: Experiment with different LSTM architecture configurations and hyperparameters to potentially enhance the model's performance.

- **Feature Engineering**: Explore the possibility of incorporating additional financial indicators or sentiment data for more accurate predictions.

- **Ensemble Techniques**: Implement ensemble techniques, such as combining multiple LSTM models, to further improve forecasting accuracy.

## Acknowledgments

I would like to express my gratitude to [Ali Reza Javid](https://www.kaggle.com/alirezajavid1999) for providing the historical stock price [Dataset](https://www.kaggle.com/datasets/alirezajavid1999/google-stock-2010-2023/code?datasetId=3570475) and to the open-source community for the invaluable resources and support.


