# Data science portfolio

This portfolio is a compilation of Notebooks in which I explore different data analysis methods and machine learning algorithms.

# Projects

# Classification problem for Identifying the Music Genre of Songs

 A custom subset of the Million Song Dataset is classified by the genre of the songs based on 264 bag-of-frames features.
 I use a borderline over-sampling method for imbalanced dataset, and use support vector machine, logistic regression and XGboost classifier algorithms for the classification.
 
  [Notebook](https://github.com/ed-datascience/Data-Science/blob/master/Notebooks/Song_Classification.ipynb)
 
 # Regression problem: House Prices: Advanced Regression Techniques
 
 This is a [Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) in which I use different regression methods to predict the sale price of houses in Ames, Iowa based on 79 different numerical and categorical features.
 
 [Notebook](https://github.com/ed-datascience/Data-Science/blob/master/Notebooks/HousePriceRegression.ipynb)
 
 # Tweet Analysis: Tweets from US congress members
 
 I collected 1000 tweets per member of US congress to analyse how differently US senators from either parties use Twitter, and if we can guess which party the senator represents using term frequency–inverse document frequency(TF-IDF) statistic and Multinomial Naive Bayes classifier.
 
  [Notebook](https://github.com/ed-datascience/Data-Science/blob/master/Notebooks/Congress_Tweet_Analysis.ipynb)
  
  # Plant Seedlings Classification
  
  This dataset is from [Kaggle](https://www.kaggle.com/c/plant-seedlings-classification). Goal is to classify different crop seedlings. For classification I use pretrained Xception model from Keras as a base model.
  [Notebook](https://github.com/ed-datascience/Data-Science/blob/master/Notebooks/Plant_Seedlings_Classification.ipynb)
  
# Tweet Semantic Analysis

A simple tweet sentiment classification using pretrained [GloVe word vectors](https://nlp.stanford.edu/projects/glove/) simple convolutional neural network. Network is roughly inspired by article [Convolutional Neural Networks for Sentence Classification](https://arxiv.org/abs/1408.5882). Dataset is trained and tested with [Sentiment Analysis Dataset](http://thinknook.com/twitter-sentiment-analysis-training-corpus-dataset-2012-09-22/) which contains 1,578,627 classified tweets, each row is marked as 1 for positive sentiment and 0 for negative sentiment.

[Notebook](https://github.com/ed-datascience/Data-Science/blob/master/Notebooks/Tweet_Semantics_Analysis.ipynb)
