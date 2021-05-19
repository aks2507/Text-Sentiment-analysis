# Project Description
Parsing texts in order to extract emotions from them. 
The process includes slicing and dicing heaps of unstructured, heterogeneous documents into easy-to-manage and interpret data pieces to classify emotions.
Emotions will be classified into five categories:
1. Extremely positive
2. Positive
3. Neutral
4. Negative
5. Extremely negative

# Abstract
Twitter is an enormously popular microblog on which users voice their opinions. Opinion investigation of Twitter data is a field that has been given much attention over the last decade and involves dissecting “tweets” (comments) and the content of these expressions.

Sentiment analysis (or opinion mining) is a common dialogue preparation task that aims to discover the sentiments behind opinions in texts on varying subjects.

In recent years, researchers in the field of sentiment analysis have been concerned with analyzing opinions on different topics such as movies, commercial products, daily societal issues etc.

This project explores the various sentiment analysis applied to COVID-19 tweet data and their outcomes

# Dataset
We are using the following dataset:

https://www.kaggle.com/datatattle/covid-19-nlp-text-classification

# Accuracies of different models used
| Multi-class Model           | Training Accuracy | Testing Accuracy |
| --------------------------- |:-----------------:| :--------------: |
| Naive Bayes                 | 68.20             | 43.89            |
| Stochastic Gradient Descent | 80.40             | 55.79            |
| Support Vector Machine      | 89.84             | 56.45            |
| Logistic Regression         | 87.14             | 61.00            |
| Bi-directional LSTM         | 81.03             | 76.46            |
