# Stock-Price-Prediction
Stock Price Prediction using Machine Learning Algorithms including Long Short-Term Memory (LSTM) networks, Linear Regression (LR), and Auto Regressive Integrated Moving Average (ARIMA) models. <br />
<br />
Machine learning models can be useful tools in predicting stock prices of a given company. Accurate predictions of a company's future stock price could yield significant profits for an entity. In this project, we use 17 year's of IBM stock price data to predict and evaluate its stock price in the last 3 years. The prices are predicted using machine learning models such as Linear Regression, Long Short-Term Memory Networks, and Autoregressive integrated moving average(ARIMA) models, and a comparison is made between the working and results of each model. The results show that the prices were most accurately predicted by the ARIMA model with a root mean squared error of 0.05, followed by LSTM with a root mean squared error of 1. Linear Regression performs the worst among all three models with a root mean squared error of 51. <br />
<br />
First, let us look at all Closing values of the IBM Stock price from 1999-11-01 to 2021-03-04: <br /> <br />
<img src="Model Results/IBM Closing Stock Price.png"> <br /> <br />
Now, let us compare the results predicted by each model vs the actual test values from 2016-09-02 to 2021-03-04: <br />
<br />
## Long Short-Term Memory (LSTM) <br /> <br />
<img src="Model Results/LSTM/LSTM test result.png"> <br /> <br />
<img src="Model Results/LSTM/LSTM test+train result.png"> <br /> <br />
RMSE: 1.06 <br /> <br />
## Linear Regression <br /> <br />
<img src="Model Results/Linear Regression/LR test result.png"> <br /> <br />
<img src="Model Results/Linear Regression/LR train result.png"> <br /> <br />
RMSE: 51.80 <br /> <br />
## Auto Regressive Integrated Moving Average (ARIMA) <br /> <br />
<img src="Model Results/ARIMA/ARIMA test result.png"> <br /> <br />
<img src="Model Results/ARIMA/ARIMA test+train result.png"> <br /> <br />
RMSE: 0.05 <br /> <br />
Thus, we see the ARIMA model performs best (with RMSE = 0.05), followed by LSTM (with RMSE = 1), and Linear Regression performs worst (with RMSE = 51).
