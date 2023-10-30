# Sentiment Analysis

This repository contains a machine learning project for predicting sentiment in text data. Sentiment analysis, also known as opinion mining, is a natural language processing (NLP) task that involves determining the sentiment or emotional tone expressed in a piece of text, such as a review, comment, or tweet. The goal of this project is to build a predictive model that can classify text data as positive, negative, or neutral based on its sentiment.

## Key Feature

* Converts all text to lowercase.
* Removes non-alphabetical characters using regular expressions.
* Removes digits (numbers) using regular expressions.
* Removes specific symbols '&' and '*' using regular expressions.
* Applies TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
* Uses a Multinomial Naive Bayes classifier (MultinomialNB).

## Deployment

https://huggingface.co/spaces/Mangara01/Sentiment-Analysis

## File Description

* **Text_Message_Analysis.ipynb:** This notebook contains the analysis.
* **clean_nus_sms.csv:** This csv file contains data for analysis.
