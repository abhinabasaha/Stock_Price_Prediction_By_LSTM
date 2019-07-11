# Stock_Price_Prediction_By_LSTM
Prediction of Google Stock price for 2017 with a record from 2012 to 2016 by LSTM with Keras.

source of dataset: https://www.superdatascience.com/pages/deep-learning

Recurrent neural networks(RNN) have connections that have loops, adding feedback and memory to the networks over time. This memory allows this type of network to learn and generalize across sequences of inputs rather than individual patterns.

A powerful type of Recurrent Neural Network called the Long Short-Term Memory Network (LSTM) has been shown to be particularly effective when stacked into a deep configuration, achieving state-of-the-art results on a diverse array of problems from language translation to automatic captioning of images and videos.

Two most important problems regarding RNN are:
1) Vanishing Pradient Problem
2) Exploding Gradient

Vanishing Gradient: Its is a situation where a deep multilayer feed-forward network or a recurrent neural network is unable to propagate useful gradient information from the output end of the model back to the layers near the input end of the model.
The result is the general inability of models with many layers to learn on a given dataset or to prematurely converge to a poor solution.
Exploding Gradient:

Here I will be using LSTM to predict the stock price of a given date considering 60 previous prices as the time step.
The dataset contains stock prices from 2012 to 2016 as traing data. Prices of January, 2017 will be used to test our model.


