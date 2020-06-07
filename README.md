# Word-Embeddings
This repo is will give an introduction to Word Embeddings and go on to doing Text classification using word embeddings

Word Embedding is a learned representation for text where words that have the same meaning have a similar representation. Individual words are represented as real-valued vectors in a predefined vector space. This is advantageous over the representaton by one hot encoding/Bag of words which has a lot of 0s in the vectors and miss out on capturing the semantic relations of words (as all words as considered to be independant).
Quick intro Reference - https://towardsdatascience.com/what-the-heck-is-word-embedding-b30f67f01c81

## Types of Word Embedding
1. Frequency based Embedding
    -Count Vectors
    -TF-IDF
    -Co-Occurrence Matrix
2. Prediction based Embedding
    -CBOW
    -Skip-Gram
Awesome read for above and more - https://www.analyticsvidhya.com/blog/2017/06/word-embeddings-count-word2veec/


# Let's start with the Classification

## Some Important Preprocessing Steps to begin with
Many of these can be done with the help of the [nltk package](https://github.com/nltk/nltk). They can be referenced in the [insert code folder link]
1. Removing Stop words
2. Tokenizing
3. Stemming
4. Lemmatization
5. Part of Speech Tagging
6. Named Entity Recognition
7. And more...
Reference - https://medium.com/@datamonsters/text-preprocessing-in-python-steps-tools-and-examples-bf025f872908


Toxic comment classification with word embeddings:

Fasttext - https://www.kaggle.com/doha2012/toxic-comment-word-embeddings-and-cnn
Glove - https://www.kaggle.com/ajithvajrala/word-embeddings-with-tfidf-ensemble
