# Personal Project 1
 ## Objective and details: 
To make predictions on the Dow Jones Index and the S&P500 index. 
The idea is to predict if the closing price on the day after a window of fixed length of days, 
is high or lower than the last day in the window.
The file: personal_project_1-ohlc_c_vs_c.ipynb is based on the Dow Jones Index, and the data is in the format 
Open, High, Low, Close.
The file: personal_project_1-ohlc_c_vs_c-Copy1.ipynb is based on the S&P 500 index, and the data is in the format 
Open, High, Low, Close, Volume, 10-day EMA, 20-day EMA, RSI.
The model used is a simple 2 layer LSTM, with a dense layer at the end. 

## Results:
The results are not fantastic. Although adding more features such as the volume, 
EMAs and RSI seems to improve the accuracy a little, overall accuracy still seems limited to the low 50s%. Nevetheless, it is a useful exercise
as an example of how to apply an LSTM to real life market data.
