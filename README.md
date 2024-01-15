# Rigor
Crypto Currency Price Prediction Model Using Sentiment Analysis and Coin Features
This is the crypto currency price prediciton model in which transformers were used to first derive the sentiments from the market and then predict the price of the correspondence currency.
Three most correlated coins were taken togethere to predict the price of any one currency.
First the top 10 coin data was extracted from yahoo finance. correlated, most correlating coins were taken
Then sentiment data was extracted from reddit and tweeter using Praw and sns Scrapper of the coins taken.
Sentiment analysis was done using FinBert , a pre-trained transformer on financial data sets.
Data was pre-processed and visulaized to understand the patterns.
Data from coin such as close, volume were combined with the senitment data.
Time Series transfromer was used to predict the price 


# About the drives in the repo


