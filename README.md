Amazon (AMZN) Stock Price Prediction
Project Overview
This project uses machine learning to predict the daily closing price of Amazon stock. I compared two models—Linear Regression and Random Forest—to see which one could better handle the stock market's movements using technical indicators.

Feature Engineering
I created three "features" from the raw data to help the models learn:

MA_20 & MA_50: Simple Moving Averages for the past 20 and 50 days.

EMA_20: An Exponential Moving Average that reacts faster to recent price changes.

Model Performance
Linear Regression: Achieved 89.31% accuracy. It created a specific formula for predicting prices:

y
^
​	
 =2.8167+1.5170(EMA 
20
​	
 )−0.5362(MA 
50
​	
 )
Random Forest Regressor: Achieved a higher accuracy of 96.66% after finalization.

Winning Feature: Both models showed that EMA_20 is the most important indicator for predicting Amazon's price.

Conclusion
The Random Forest model was more accurate (96.66%) than the Linear Regression model (89.31%). This shows that for complex stocks like Amazon, a model that uses "decision trees" (Random Forest) often performs better than a simple straight-line model.
