# Restaurant-Review-Sentiment-Analysis

![alt text](https://github.com/vishvpatel-97/Restaurant-Review-Sentiment-Analysis/blob/main/README-Resources/restaurant.jpg)

## Web App on heroku

![alt text](https://github.com/vishvpatel-97/Restaurant-Review-Sentiment-Analysis/blob/main/README-Resources/restaurant.gif)

[App link](https://restaurants-sentiment-analysis.herokuapp.com/)

## Details of the project

### Dataset

![alt text](https://github.com/vishvpatel-97/Restaurant-Review-Sentiment-Analysis/blob/main/README-Resources/dataset.jpg)

## Overview

- Dataset has 10000 rows and 7 columns.
- We have to predict whether a review is "Positive" or "Negative".
- PortStemmer method has been used for Stemming.
- I have also tried WordEmbedding with LSTM.
- I have applied many different algorithms LSTM, Bi-Directional LSTM, RandomForestClassifier, MultinomialNB, SVM and KNN.

## Details
- After cleaning the columns, I converted "Rating" Column, which is actually a numerical column, into the column that has two labels "Positive" and "Negative".
- I considered Rating Above 3 as "Positive" and Below 3 as "Negative".
- To understand detailed Project approach, check my restaurant-review.ipynb or app.py
- This project has around 10,000 Reviews, so for CountVectorizer, max_features=9000 gave best results after trying values like 2500, 5000, 7500... Which I think is most important thing to achive higher accuracy value.
