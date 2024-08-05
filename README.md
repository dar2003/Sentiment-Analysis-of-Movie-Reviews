# Sentiment-Analysis-of-Movie-Reviews


**Overview**


This project focuses on analyzing the sentiment of IMDB movie reviews. Using machine learning techniques, it classifies reviews as positive or negative.



**Dataset**


Source: IMDB Dataset of 50K Movie Reviews

Structure: The dataset contains 50,000 reviews, evenly split between positive (25,000) and negative (25,000) sentiments.


**Preprocessing**


**Text Cleaning:** Removal of HTML tags, punctuation, and converting text to lowercase.

**Tokenization: Splitting text into words (tokens).**

**Removing Stop Words:** Excluding common words that do not contribute to sentiment.

**Stemming and Lemmatization:** Reducing words to their base or root form.


**Feature Engineering**


**One-Hot Encoding:** Converting categorical sentiment labels (positive, negative) into binary form.

**Label Encoding:** Mapping sentiment labels to numerical values (positive -> 1, negative -> 0).


**Model Training**


Algorithms Used: Various machine learning algorithms including Logistic Regression, Random Forest, and Neural Networks.


**Evaluation Metrics: Accuracy, Precision, Recall, F1 Score.**


**Results**


Best Model: Logistic Regression

Accuracy: 88%

Precision: 0.89

Recall: 0.87

F1 Score: 0.88
