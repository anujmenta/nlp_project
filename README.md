# QuoraChallenges-Labeler
**Document similarity with tf_idf and cosine similarity and word2vec**

The challenge is to predict categories for a question using labelled training data. Complete problem description can be found here - https://www.quora.com/about/challenges#labeler

The solution is to find feature vectors for labelled questions by calculating word vectors of each word in the question and finding out the centroid of all the words to represent the question. Then calculate the cosine similarity between questions to find the most similar question.

tfidf.py - Tf-Idf approach to solve the problem statement
word2vecapproach.py - Word2Vec approach to solve the problem statement
demo.py - Run the file to start a demo. Enter question and the number of most similar questions required and find the most similar question.
finalscorer.py - Run script to obtain score.(Given by quora)