# Sentimental-Analysis

Dataset: dataset contains 1.6 million tweets with 800000 positive and 800000 negative tweets.

Cleaning of data using regex is done. Username with most positive and negative tweets along with the words most used in positive and negative used and listed down.

Stemming and Tokenization is used to prepare it for the model.

Sequential LSTM model is prepared with 7 layers with an embeding layer in the starting followed by LSTm, dropout, LSTM, dense, dense layers.

Accuracy of model is 77%, some overfitting is observed but can be reduced by increasing droupout or tunning some parameters. 
