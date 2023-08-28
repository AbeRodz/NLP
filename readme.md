# Natural Language Processing Class

![alt text](./images/maxresdefault.jpg "nlp")
***This repo is for the NLP class***

# First challenge

The first challenge consisted in implementing from scratch some concepts such as one-hot encoding, tf-idf and cosine similarity between vectors.


# Second challenge

The second challenge consisted in making a chatbot using spaCy and Tensorflow, of the type intent, pattern, and response, using dense layers.

# Third challenge

This challenge introduced word embeddings with Gensim, using plato's republic as a corpus and word2vec a model was trained, the embeddings can be visualized using matplotlib, and we can even find the most similar words in the embeddings space using the trained model.  

# Fourth challenge

This challenge uses Embeddings with and LSTM model, using plato's republic as a corpus we now train this model to predict the next word of an input text.


# Fifth challenge

Using LSTM and word embeddings a sentinemt analysis model was developed using 
an [E-commerce dataset](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews) from kaggle, the dataset has the review of a an item divided into 5 categories, for simplicity it was encoded onto 3 categories, due to high class imbalance, this was a good a approach, but an class oversampling was also performed. The model got an f1 score of 62% on testing.

# Sixth challenge

A QA bot was made with an LSTM-based model, this model uses embedding layers, LSTM, and dense layers, it has 5104399  trainable parameters, although during inference, the model performed average, as this model tend to respond repetitive answers.
