# Sentiment Analysis

## Key Feature

Text Preprocessing:

* Converts all text in the 'Message' column of the DataFrame df to lowercase.
* Removes non-alphabetical characters from the 'Message' column using regular expressions.
* Removes digits (numbers) from the 'Message' column using regular expressions.
* Removes specific symbols '&' and '*' from the 'Message' column using regular expressions.

Sentiment Analysis:

* Splits the data into training and testing sets with a 70/30 split ratio.
* Applies TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
* Uses a Multinomial Naive Bayes classifier (MultinomialNB).

## Deployment

https://huggingface.co/spaces/Mangara01/Sentiment-Analysis

## File Description
  
### Text_Message_Analysis.ipynb:

This notebook contains codes for Sentiment Analysis.

### clean_nus_sms.csv:

This csv file contains tables for analysis.
