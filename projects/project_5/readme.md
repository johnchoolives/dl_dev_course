# Personal Project 2
## Objective: 
To use LSTM to make predictions real life market data. The idea is to predict the second half of the trend of a market using the data from the
first half of the trend.
## The Data:
Using the Dow Jones Index daily Open, High, Low, Close since 1985.
## The Models:
A simple 2 layer LSTM with a dense layer at the end. The idea is to classify whether the trend for a window period is going to
be uptrend, downtrend or flat (no trend). For this example, I use a window period of 20 days, so in effect, I am trying to predict
the trend of 20 days using only the first 10 days of data.
## The Result:
Result is quite encouraging, with an accuracy rate of about 63%.
