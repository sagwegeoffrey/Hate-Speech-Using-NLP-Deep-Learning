# Hate-Speech-Using-NLP-Deep-Learning
This repository contains Hate Speech mini project for Kenyan Election leveraging on NLP and Deep Learning.

Deep NLP for Hate Speech Detection

Hate Speech Detection task on Social Media
Hate Speech Detection is the automated task of determining whether a piece of text contains hateful/offensive content.
We built a classifier using PyTorch and a pre-trained BERT model leveraging on Psycho-Social features. A twitter Corpus study of the 2007 and 2017 Kenyan Elections on the Basis of Offensive speech.
The objective of this task is to detect the sentiments of the tweets in realtime for the specific keyword of Hate Speech. WordCloud is used to get the tweets in realtime for the corresponding keyword.  PorterStemmer is a pretrained sentiment analysis model used to detect the sentiments and normalize the tweets.
The hate_speech text is a highly unstructured form of data, various types of noise are present in it and the data is not readily analyzable without any pre-processing. The entire process of cleaning and standardization of text, making it noise-free and ready for analysis is known as text preprocessing. Given a training sample of tweets and class, where class ‘1’ denotes the tweet is offensive and class ‘0’ denotes the tweet is not offensive, the objective is to predict the class on the given test dataset.

We establish a new psychosocial feature set used to identify subtle forms of hate speech, particularly in codeswitched text messages exchanged on social media, 
and test this by training a machine transformer model (BERT) that could generalize to other types of hate speech. To ensure that the core purpose is addressed 
completely, the objectives included the creation of a dataset representative of hate speech on social media in Kenya, the development of a deep learning and 
transformer model based on the psychosocial features, and the evaluation of the hate speech deep learning and NLP model. 
