# Multi-Label Text Classification of Text Document or News

## DATASET
Toxic Comment Classification dataset. a multi-label text classfication data consisting of many wikipedia comments which have been labeled by humans according to their relative toxicity comments labels such as "toxic", "severe_toxic", "obscene", "threat", "insult", and "identity_hate". The dataset has approximately ~160k observation in total, ~125k with zero labels (toxicity) of any type, and approximately ~35k classified in one or more toxicity categories.

* Dataset Link: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge


### DATA CHARACTERISTICS (TRAIN DATASET)
* Number of data points 159571
* Number data points of type toxic 15294
* Number data points of type severe_tocic 1595
* Number data points of type obscene 8449
* Number data points of type threat 478
* Number data points of type insult 7877
* Number data points of type identity_hate 1405
* Observations in one or more class 35098
* Unclassified observation 124473


### DATA PREPARATION
 We clean the Train and Test data, specifically remove punctuations
 
 
 
### DATA PREPROCESSING
Deep Neural Networks input layers make use of input variables to feed the network for training the model. But in this task (experiment), we're dealing with words text. How do we represent these words in order to feed our model?

In our experiment, we used densed representation of those text (comments) and their semanticity together. The advantage of using this approach is the best way for fitting neural networks onto a text data (as in our case), as well as less memory usage compared to other sparse representation approaches.


### METHODS

#### Word Embedding
Two ways to feed embeddings to neural networks:

* Using your own word embeddings by training (keras)
* Using pre-trained embedding (e.g Word2vec, FastText, and Glove)


#### Without pre-trained embedding
* NN
* CNN 
* RNN
* LSTM
* GRU

#### with pre-trained embedding (with Word2Vec, FastText, Glove)
* CNN 
* RNN
* LSTM
* GRU


### EVALUATION METRICS
* Accuracy
* Score
* Precision
* F1 Score or Measure
* recall
