# Word-Embeddings
Intro to Word Embeddings and Text classification using word embeddings

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
Awesome read - https://www.analyticsvidhya.com/blog/2017/06/word-embeddings-count-word2veec/

Toxic comment classification with word embeddings:

Fasttext and - https://www.kaggle.com/doha2012/toxic-comment-word-embeddings-and-cnn
Glove - https://www.kaggle.com/ajithvajrala/word-embeddings-with-tfidf-ensemble
