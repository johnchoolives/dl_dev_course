This notebook is an lstm project on the stock market index Nikkei 225. 
The data file is a csv file of the daily closing price since 1965. It is just 1 column of closing prices. The LSTM model takes 20 days data to predict whether the 21st day is higher or lower the 20th day. if the closing price is the same, it is considered lower.
After 200 epochs of training, the model accuracy is approx 52%. This project can be considered a toy example of how to use an lstm. 
