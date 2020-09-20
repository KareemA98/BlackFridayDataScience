# BlackFridayDataScience
This a side project which is trying to score highly on a data science challenge proposed by Analytics Vidhya.
The challenge is a regression task for predicting the purchase price for products based on the product and the user purchasing.

Challenge Link: https://datahack.analyticsvidhya.com/contest/black-friday/#About

* Produced a working solution to the problem proposed.
* The solution is currently ranked 360th in the leaderboards.
* Many data science techniques used most notably the use of embeddings.
* Currently still in progress hoping to improve the score.

## Process
1. Data exploration was done to understand the dataset and the type of data being used.
2. Data transformation was done over the entire dataset so that it can be successfully pipelined into the proposed machine learning model.
3. The proposed model has many layers and inputs; it has two embeddings layers which take in different features and have an LSTM at the end of them. 
The results of the two LSTMs are combined with additional data and feed into multiple dense layers to predict a final value.
4. The results have been transformed so that they can be uploaded for submission.

## Libraries used

Python Libraries:
* Numpy
* Pandas
* Sci-Kit Learn
* Keras
