# Hackwagon_FinalProject

My final project for the Hackwagon DS102 Data Science course. It is a notebook on predicting historical stock prices based on machine learning, and comprises 3 main sections.

**1) Prediction using sentiment analysis on news articles and tweets**


![Sentiment Analysis](https://i.imgur.com/sserido.png)


I utilized **Selenium for Python** to scrape web articles from financial news sites such as CNBC, Financial Times etc. and the Twitter API for collecting tweets relating to a stock's ticker symbol. After aggregating this data, I used the NLP library **NLTK for preprocessing and VADER for sentiment analysis**.  


**2) Prediction using technical indicators and machine learning algorithms** 


![ARIMA](https://i.imgur.com/GfWT6r2.png)


Explored predicting APPL stock prices using the simple moving average and exponential moving average indicators, as well as the **ARIMA RNN**, evaluating their performance against the target price with root mean squared error (RMSE).  

**3) Simulated investing using a reinforcement learning model**

![Reinforcement Learning](https://seraphimstreets.imgur.com/all)

Trained a **reinforcement learning agent to trade 3 different stocks with Q-learning**, with the aim of maximizing returns over many iterations on the train set. A group of agents were then tested against a holdout validation set, where most were successful in reaping profits, with the mean profitability being 50% over 5 years. 

Conclusion: Machine learning (and deep sequential models especially) are highly applicable for use in financial trading, which is why they have been ubiquitously adopted by hedge funds and financial insitutions around the globe. However, for the everyman with limited budget and compute, it is still best to exercise caution when utilizing these algorithms. Although most agents were successful during evaluation, there were still a few that lost money or had earnings below the annual rate of inflation. 
