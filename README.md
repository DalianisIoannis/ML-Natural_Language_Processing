# ML-Natural_Language_Processing

Projects implemented for the Course "Artificial Inteligence II" (Spring 2021).

## Exercise 1

Implementation of gradient descent, stochastic gradient descent and mini-batch gradient descent for ridge regression in the toolkit Scikit-Learn. Use of the [California Housing Dataset](https://drive.google.com/file/d/1VUn2WKkKeRXwH02K9bqH98KjPxrUmgXh/view) to demonstrate the algorithms.

Development of a sentiment classiffier using logistic regression for the [Twitter sentiment classiffication dataset](https://drive.google.com/file/d/1dTIWNpjlrnTQBIQtaGOh0jCRYZiAQO79/view) Evaluation of the classiffier using precision, recall and F-measure.

## Exercise 2

Sentiment classiffier using feed-forward neural networks for the [Twitter Sentiment Analysis Dataset](https://drive.google.com/file/d/1dTIWNpjlrnTQBIQtaGOh0jCRYZiAQO79/view).

Implementation of four models for the specific task.

*FNN_GLOVE.ipynb: Use of Glove data file to build corpus.
*TRY_FFNN.ipynb: Only difference with FNN_GLOVE.ipynb is the use of corpora package from the gensim library. Very slow model.
*AI2_FFNN.ipynb: Use of BERT pretrained model.
*AI2_NOT_FFNN.ipynb: CNN and RNN using Glove.

## Exercise 3

Sentiment classiffier using a bidirectional stacked RNN with LSTM/GRU cells for the [Twitter sentiment analysis dataset](https://drive.google.com/file/d/1dTIWNpjlrnTQBIQtaGOh0jCRYZiAQO79/view). One of the notebooks is enriched with Attention.

## Exercise 4

Document retrieval system to return titles of scientific papers containing the answer to a given user question. We use the [COVID-19 Open Research Dataset (CORD-19)](https://ai2-semanticscholar-cord-19.s3-us-west-2.amazonaws.com/historical_releases/cord-19_2020-03-13.tar.gz) (articles in the folder comm_use_subset).

Two implementations, one with doc2Vec and one with Sentence-Bert.

For example, for the question "What are the coronaviruses?", the system can return the paper title "Distinct Roles for Sialoside and Protein Receptors in Coronavirus Infection" since this paper contains the answer to the asked question.

Other questions can be found [here](https://drive.google.com/file/d/1XxqGTttbTqcrC88M3ZerpsCS10L0tVME/view?usp=sharing.
