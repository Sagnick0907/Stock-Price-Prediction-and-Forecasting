# Apple Stock-Market-Forecasting

## Table of Content
  * [Overview](#overview)
  * [Technical Aspect](#technical-aspect)
  * [Technologies Used](#technologies-used)

## Overview
This is a Apple's Stock Price Forecasting Deep Learning Project which uses Stacked [LSTM](https://colah.github.io/posts/2015-08-Understanding-LSTMs/) to forecast the stock price of the Apple Company for the next 30 days.  

## Technical Aspect
Dataset Link: https://www.tiingo.com/  
Contains data ranging from **2017-01-30 to 2022-01-27**.
Given below are the steps taken to build the model:  
-	Imported the **'AAPL.csv'** Dataset & reset the index.
-	Applied **MinMax scaler** on data.
-	Splitting Dataset into **train and test split**.
-	Converted the array of values into a **Dataset matrix** & Reshaped it for giving it as **input to our Model**.
-	Created the **Stacked LSTM model**.
-	**Trained** & **tested** the model.
-	Calculated the **RMSE** performance metrics. ( **Train Data RMSE = 205.95, Test Data RMSE = 141.13**)
-	Plotting Data.  
![image](https://user-images.githubusercontent.com/76872499/151657651-98960e17-dca5-45c2-b1b4-5188c1446f9b.png)

- Predicted the Next 30 days & Plotted the graph for that Data.  
![image](https://user-images.githubusercontent.com/76872499/151657636-a63df598-be12-4ba1-aab9-8bbea9b2da79.png) ![image](https://user-images.githubusercontent.com/76872499/151657669-4f158c82-74b6-4e3c-9241-dc940c3c34c4.png)

## Technologies Used
- Jupyter Notebook
-	ML model: Customized LSTM Model
-	Libraries: pandas, pandas_datareader, numpy, matplotlib.pyplot, math, tensorflow, sk-learn.
