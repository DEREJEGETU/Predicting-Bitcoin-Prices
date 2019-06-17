# Predicting the Price of Bitcoin : An Exploration of Different Machine Learning Algorithms
*This project is a final capstone project for Nashville Software School Cohort 1 Data Science bootcamp.* 

## Introduction
Cryptocurrencies are known for their high volatility movement. They exhibit a random walk movement, which makes prediction difficult like other financial assets.  Though it is difficult to perfectly predict cryptocurrencies movement, their a high likelihood of identifying the signal and direction of the movement. The fast pace of machine learning and AI development is helping for a better prediction of the prices of financial assets including cryptocurrencies. However, as far as my knowledge no one has openly declared if they are able to make a quite accurate prediction. This inspire me to throw my stone and to learn from the process.  

## Research Question 
I have raised two research questions
* Is it possible to predict BTC price fluctuation ?
* How about the direction of  the fluctuation, are their signals? 
## Data and Methodology

### Data
Following the works of (Jang & Lee, 2018; Poyser, 2017; Kavvadias, 2017 and Li et al., 2018), we grouped the drivers of the price fluctuations for cryptocurrencies in to two. These are the internal determinants and the external determinants. The internal determinants are inherent to cryptocurrencies block chain formation, a core technology of cryptocurrencies. The second group is the external determinants are related with the financial aspects of Bitcoin or any other cryptocurrencies. Hence, we have used quandl <https://www.quandl.com> and yahoo finance <https://finance.yahoo.com> to collect data. Some of the data collected are hash rate,transaction volume, market capitalizations, Difficulty , Miners revenue, USD / Major Exchange rates, VIX, S&P 500 and others. 


### Methodology 
In this project, a step by step approach will be employed to determine the best fit models. The following ARIMA and Recurrent Neural Network Models were explored
  * Autoregressive Model(AR)
  * Moving Average Model (MA)
  * Autoregressive Integrated Moving Average(ARIMA)
  * ARIMAX model 
  * Long Short Term Memory (LSTM) from Recurrent Neural Networks (RNN)
  * Fbprophet Model 

 **Note: This notebook is just only for learning purpose and I do not advise to use it for financial decision making.** 
