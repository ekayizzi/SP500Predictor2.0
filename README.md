# SP500Predictor2.0

Stock Market Predictor Using Machine Learning & News Sentiment Analysis

This code features a predictive model for the S&P 500 index. 
This was made possible by leveraging machine learning techniques and using historical stock data to achieve an accuracy rate of 58%.

Furthermore, there is an implementation of a text analysis function to categorize real-time news from Yahoo Finance 
as ‘bullish’ or ‘bearish’. This is done by scraping Yahoo Finance and looking for terms that mention inflation, the federal reserve, or interest rates, then after we integrate market sentiment based on the context around these terms and how it affects the index. From there we return sentiments and translate then into something that can adjust the machine learning predictions around real-time news.

Additionally, there is a newly added function that also incorporates the market fundementals and context surrounding Apple and Microsoft (the stocks with the biggest market caps in the S&P500) to adjust predictions of the model based on their earnings, guidance, revenue, and expectations. 

The culmination of these additional functions enhance the accuracy of S&P 500 Machine Learning predictions.


To allow for continous improvements on the Machine Learning Model, an effective back testing strategy was implemented to 
assess model performance over time and improve it.
