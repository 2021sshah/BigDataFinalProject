# Big Data Final Project
## Training LSTM models to predict stock index prices from sequential historical data and financial news sentiment

This project utilizes LSTMs and GRUs with both news sentiment and historical time-series stock index movement as features to predict the daily closing price of stock indexes (Starting with DJIA). 

The [ProsusAI FinBERT pre-trained transformer model](https://huggingface.co/ProsusAI/finbert) was used to extract sentiment from each article in the following financial news [dataset](https://www.kaggle.com/datasets/notlucasp/financial-news-headlines?select=guardian_headlines.csv). These were aggregated and averaged to obtain sentiment scores for each day, which were included in the predictive model. The cleaned and extracted daily sentiment data can be found in the [Financial News Sentiment CSV](https://github.com/2021sshah/BigDataFinalProject/blob/main/Financial_News_Sentiment.csv).
