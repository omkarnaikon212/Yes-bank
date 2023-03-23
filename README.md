Using data visualization on our target variable, we can clearly see the impact of 2018 fraud case involving Rana Kapoor as the stock prices decline dramatically during that period.

After loading the dataset, we found that there are no null values in our dataset nor any duplicate data.
There are some outliers in our features however this being a very small dataset, dropping those instances will lead to loss of information.
We found that the distribution of all our variables is positively skewed. so we performed log transformation on them.
There is a high correlation between the dependent and independent variables. This is a signal that our dependent variable is highly dependent on our features and can be predicted accurately from them.
We found that there is a rather high correlation between our independent variables. This multicollinearity is however unavoidable here as the dataset is very small.
We implemented several models on our dataset in order to be able to predict the closing price and found that all our models are performing remarkably well and Elastic Net regressor is the best performing model with Adjusted R2 score value of 0.9932 and scores well on all evaluation metrics.
All of the implemented models performed quite well on our data giving us the Adjusted R-square of over 99%.
We checked for presence of Heterodasceticity in our dataset by plotting the residuals against the Elastic Net model predicted value and found that there is no Heterodasceticity present. Our model is performing well on all data-points.
With our model making predictions with such high accuracy, we can confidently deploy this model for further predictive tasks using future data.
