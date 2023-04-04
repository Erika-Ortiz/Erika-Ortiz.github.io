---
layout: default
date: 2023-02-27
modal-id: 2
modal-id-str: sentiment_analysis
img: project_card_2.png
alt: image-alt
category: Machine learning - NLP
title: sentiment analysis on movies reviews
technology: Pandas, Numpy, Spacy, NLTK, Gensim, Sci-kit learn, Docker, AWS (EC2) 
description: This project involved training a sentiment analysis model to predict positive and negative opinions in movie reviews, using a binary classification approach with labels of 'positive' and 'negative'. <br><br>  &nbsp;&nbsp Our first step was to prepare the data by reading files from the <a class="plinks" href=https://ai.stanford.edu/~amaas/data/sentiment/ target="_blank">Large Movie Review AI Stanford Dataset</a>, which were in text format and required some preprocessing to be used in the model. Next, we focused on normalizing the dataset, with the most important and challenging aspect being the pre-processing of the text. To accomplish this, we created a set of python functions and scripts for text normalization. <br><br>  &nbsp;&nbsp We then moved onto feature engineering, using classical vectorization BoW and TF-IDF to vectorize the data and apply machine learning models. The performance of these models was evaluated using ROC AUC. After that, we developed our own word embedding by tokenizing reviews and training it for use as a vectorization source. The following step was improve our original embedding by increasing vector size, avoiding lemmatization or stemming, and incorporating unlabeled reviews  reserved for unsupervised learning. <br><br>  &nbsp;&nbsp Finally, we compared the performance of the classical vectorization methods with our improved word embeddings using python functions to plot the models' performance in a single graphic. Additionally, we trained a model using the Gensim Library's glove-wiki-gigaword-300 model. Through the project we work with all components containerized in Docker, allowing for Jupyter Notebook to run on a Docker instance on local machines as well as EC2. 

---
