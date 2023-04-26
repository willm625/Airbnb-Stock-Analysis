# Airbnb-Stock-Analysis
This notebook's aims to find a model that accurately predicts future stock value for Airbnb given data for the 2021-22 fiscal year. Specifically, the Daily Closing and High stock values were predicted using a variety of Regression models including Linear, Lasso, Ridge, and Random Forest Regressor. Then the model that performed best wsa optimized using Principal Component Analysis.\
\
The dataset was obtained from Kaggle via this link: https://www.kaggle.com/datasets/whenamancodes/airbnb-inc-stock-market-analysis \
\
In predicting the closing and high stock values it was found that the Linear Regression performed best, but when PCA was applied it overfit the data. There was an improvement in performance for the training set but a decrease in the testing set. In conclusion, it seems a normal Linear Regression model can correctly predict at least 98% of unseen data.
