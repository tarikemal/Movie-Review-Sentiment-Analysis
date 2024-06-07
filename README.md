# Movie-Review-Sentiment-Analysis

This is a sentiment analysis project on IMDB movie reviews dataset. It is a binary classification task. I used bag of words and word embedding (Glove) techniques to represent the review texts. While Multinomial Naive Bayes and Logistic Regression algorithms perform worse on embeddings, KNN expectedly performs better. This is because the input size is much smaller in word embeddings (300) and KNN performs better in smaller vector spaces. 
