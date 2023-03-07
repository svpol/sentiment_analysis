# Sentiment analysis

This is an NLP project illustrating sentiment analysis.

## Data

A data set with film reviews from IMDB is taken and placed to `movies.csv`. 
The source is https://www.kaggle.com/datasets/yasserh/imdb-movie-ratings-sentiment-analysis.

The dataset has the following columns:

1. `text` - film reviews from IMDB, string;
2. `label` - int: `0` if the review is negative, `1` if the review is positive.

## Task

The task is to make a prediction for each review whether it is positive or negaive, i. e. to set one of two labels: 0 or 1.

## Methods

The pipeline is the following:

1. Different variants of vectorization are made: BOW and TF-IDF.
2. ML models are applied to the vectorized text data.
3. Accuracy score is calculated for each model.
4. Choose the best prediction model.
