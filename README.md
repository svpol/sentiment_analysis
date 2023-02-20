# Sentiment analysis

This is an NLP project illustrating sentiment analysis.

A data set with film reviews from IMDB is taken and placed to `movies.csv`. The source is https://www.kaggle.com/datasets/yasserh/imdb-movie-ratings-sentiment-analysis.

The dataset has the following columns:

1. `text` - film reviews from IMDB, string;
2. `label` - int: 0 if the review was negative, 1 if the review was positive.

The task is to make a prediction for each review whether it is positive or negaive, i. e. to set one of two labels: 0 or 1.

Prediction is made via BOW and TF-IDF vectorization and ML models applied to the vectorized text data.

Accuracy score is calculated for each model.
