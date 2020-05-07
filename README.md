# Module 4 Project - Stock Predictions

##[Presentation](https://github.com/geomms/Mod4_Project/blob/master/Picking%20Bearish%20Entries.pdf)

### Goals
The purpose of stock predictions is to outperform the market. This means generating returns that would be greater than simply buying and holding a security. In order to accomplish this we can try to:

- Predict ideal entry and exit points for trading securities
- Forecast future prices

## Data used: Yahoo Finance library to pull stock data
![Stock Chart](https://www.liberatedstocktrader.com/wp-content/uploads/2009/03/NFLX-Basic-Chart-Volume-696x356.jpg)

## Project Objective:

- Forecast prices for better trades
  - [SVR Model](https://github.com/geomms/Mod4_Project/blob/master/SVR%20Model.ipynb)
  - [ARIMA Model](https://github.com/geomms/Mod4_Project/blob/master/ARIMA%20Model.ipynb)
  - [Price Forecast](https://github.com/geomms/Mod4_Project/blob/master/Price%20Forecast.ipynb)
  
- If forecasting is not accurate, predict entries and exits or long and short positions
  - [Ichimoku Cloud](https://github.com/geomms/Mod4_Project/blob/master/Ichimoku%20Cloud.ipynb)
  - [Logistic Regression](https://github.com/geomms/Mod4_Project/blob/master/Logistic%20Regression%20Model.ipynb) 
  
### Metrics Used:
- Cross validation score mean

### Methods Used
* Statistics
* Data Cleaning
* Data Organizing/Exploring
* Feature Engineering
* Machine Learning
* Data Visualization
* Predictive Modeling
* Logistic Regression

### Solutions:
- Selecting the right features and checking score results of models
- Use noncolinear technical indicators to improve accuracy and reduce overfitting
- Complicated problems do not always have to have complicated solutions

## Project Findings:
- Using more features did not necessarily imporve the model
- Trying to forecast future prices was difficult
- More optimal to find long/short entries
- Model predicted 85% accuracy for short positions, 68% for long positions
- Features and models are better at choosing shorts rather than longs
- Other models were not used as they were less accurate or provided returns worse than buying and holding

## Recommendations for further developments:
- Develop other models to improve accuracy
- More stocks to analyze
- Predict long/short positions closer to trade time vs. backtesting
  ### Further Analysis
 - Improve accuracy for long entries
 - Build algorithm using predictions to execute trades
