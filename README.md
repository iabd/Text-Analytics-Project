# Sentiment Analysis using Convolutional Neural Networks

This project was part of the academic credits in Text Analytics. Originally, it is the work of  Kim Yoon described in the paper: [Convolutional Neural Networks for Sentence Classification (EMNLP 2014)](https://arxiv.org/abs/1408.5882). This project implements the methodologies using Keras, NLTK, Gensim on [Sentiment140 dataset](). 
Sentiment140 dataset is a collection of 1.6 million tweets with sentiment annotated from 0-4 (negative-positive).

### Requirements

The code requires Python>=v3.6 with the libraries which can be installed using

`pip3 install tensorflow keras gensim numpy sklearn nltk pandas`


### Project

Given below is the list of files with description:
* `Main.ipynb` : The IPython notebook file containing preprocessing, word-embedding, model definition and training. 
* `trainW2V` : Word2vec embeddings
* `project140.h5` : Model checkpoint
* `sent140Vocab.csv` : Vocabulary of the word embeddings
* `sentiment140test.csv` : Test file
* `sentimentClassifier.mlmodel` : CoreML file for integration into iOS app.
* Other txt/csv file contains data that can be used for the inference/fine-tuning.  

