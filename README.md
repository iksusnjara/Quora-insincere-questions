# Quora-insincere-questions

This project contains Jupyter notebooks containing code for building models and solutions for Quora Insincere Questions Kaggle competition.

Qoura is one of world's leading internet forums for asking questions related to any topic: any Internet user can register and post a question about any topic and hope for answer. However, Quora's policy is that questions have to be sincere: they are posted with genuine need for gaining information, and not to make a statement. Questions considered insincere are ones having non-neutral or derogatory tone towards individuals or groups of people, those not grounded on reality etc. More details at https://www.kaggle.com/c/quora-insincere-questions-classification/data


# Motivation

This project was done for the purposes of university course with aim of practicing machine learning. Course allowed free choice of project topic, and I chose NLP as an area of personal interest.

With real life data from this Quora competition, I had a chance to practice processing textual data written in natural language in both supervised (sincere vs insincere questions) and unsupervised context.


# Technologies used

Python 3.7. with Anaconda distribution - Jupyter notebooks.

Python libraries used:
- numpy
- pandas
- matplotlib.pyplot
- scikit-learn
- nltk


# Additional notes

All the analysis was conducted on 200 000 randomly selected questions from the training dataset. This was done to speed up algorithms, although at the end it seems dataset size did not affect runtime greatly. Testing was done with another 20 000 random samples drawn from the same dataset.

NLP approach used in this project was Bag of Words - embedding texts in vector space of words used in them, with word counts as values in matrix. Along with single words, bigrams and trigrams were also used. This matrix was basis for further transformations and algorithms, as can be seen in notebooks.
