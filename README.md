# ML-Model-for-Close-Price-Prediction

Created a Machine Learning model that tries to predict the Close Price of any arbitrary stock (in this case, it is Apple) using historical data and techincal indicators.

Linear Regression is one of the most interpretable and practical models for financial prediction — especially when one is just getting into quantitative modeling.

Deployed Feature Engineering indicators such as SMA (Simple Moving Average), EMA (Exponential Moving Average), Daily Returns and Lagged Prices 

Things that can be learnt from this model: 
a. Feature engineering: Replicates human trading logic
b. Time-based split: Preserves causal relationships
c. Model interpretation: Coefficients show variable impact
d. Regression evaluation: Helps quantify model reliability

Furthermore, I calculated thr RMSE (Root-Mean-Squared Error) to measure the average distance between the predicted price and the actual value and the R² Score (Coefficient of Determination) to measure how well the variance in the data is explained by the model. 

Using the model in this project and the stock, I achieved the following values:
RMSE: 0.9852435371789068

R² score: 0.9987774257100636

In an efficient model, low RMSE means that the predictions deivating less from actual stock price. In this case, the RMSE is 0.985 which shows less than < 0.5% error, which implies that the predictions are less than $1 off. R² Score in the model is 0.9988, it means that the model explains 99.88% of the variance in stock prices. It furhter implies that the model almost entirely captures the underlying structure of the data.

Finally, I plotted a graph between Actual Price and Predicted Price to see the results visually which makes them easy to interpret. 
