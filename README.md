# Stock price prediction using Linear Regression

This project is based on a tutorial from [Predicting Stock Prices with Python using Machine Learning - Linear Regression
](https://www.youtube.com/watch?v=AXBhrLongC8). The idea behind using linear regression to predict the stock price involves leveraging lagged returns data. The linear regression is fitted using lagged returns data as predictor variables and actual returns as a response variable. If the predicted return is positive, the asset is assumed to be bought/held and if the predicted return is negative, the asset is assumed to be shorted. 

Linear regression is one of the most primitive methods for stock price prediction. The coefficients in a linear regression model show how much of an impact each predictor in the model has, making it easier to understand the influence of historical data on future stock prices. Creating a linear regression model is computationally efficient, but it is not able to capture nonlinear behaviour of a stock price. However, it can serve as a good basis for understanding predictive models of the stock market, upon which more complicated predictive models could be built in the future.

## Additional analysis

In this notebook I added several minor additions to the initial analysis performed on the video from [Algovibes Youtube channel](https://www.youtube.com/@Algovibes)

- Added a scatter plot of predicted and actual results
- Calculated MAE, MSE and RMSE values
- Calculated residuals and plotted their distribution
- Assessed whether residual distribution is normally distributed and general performance of the model
