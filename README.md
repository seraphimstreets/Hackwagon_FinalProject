# Hackwagon_FinalProject

My final project for the Hackwagon DS102 Data Science course. It is a notebook on predicting historical stock prices based on machine learning, and comprises 3 main sections.

1) Prediction using sentiment analysis on news articles and tweets 

I utilized Selenium for Python to scrape web articles from financial news sites such as CNBC, Financial Times etc. and the Twitter API for collecting tweets relating to a stock's ticker symbol. After aggregating this data, I used the NLP library NLTK for preprocessing and VADER for sentiment analysis. Unfortunately, I found that I could not find a convincing correlation between these textual sources and the movement of stock prices. I proffered some possible reasons for this including: 1) VADER sentiment analyzer was trained on tweets and not financial texts, 2) Time lag between news and daily price changes, 3) Limited sample size 

2) Prediction using technical indicators and machine learning algorithms 
