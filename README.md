# Stock_prediction

### Purpose
Using variaty time series appoarches to conduct the next day prediction of stock.

### Datasets
Datasets is from yfinance (open data sourse)

### Methods
1. Divide data sets into 70% of training and 30 % of validation.
2. Train model based on different apporaches.
Simple RNN
LSTM
CNN-LSTM 
GRU
GRU-1D with CNN
3. Getting last number (time steps) rows and converting it to testing set
4. Apply different model to conduct the prediction for next day.
