# IMDB-Sentiment-Analysis with naiveBayesClassifier
Prediction of sentiments of movie reviews using Naive Bayes Classifier

Naive Bayes is a generative classifier which assumes that all the features presemt in data are independent frm each other.
This assuption may not always be true, but it does work well in most cases.

In the case of classifying movie reviews, the features are the words themselves.
The conditional probability of each word (given the review Y=1 or Y=0) is directly proportional to the posterior probability i.e P(Y|X), and can hence be used for classification directly.

If for a test example, product of P(Y=1|Xi) > product of P(Y=0|Xi), then it is classied as positive class. Otherwise, it is classified as a negative class.

The data set is split into different proportions of training and test set to observe how the probability is affected by training data size.

The data used for this problem can be found at:
https://drive.google.com/file/d/1psHPXv1sUGxSI1WsYFpUEYwilVaa-U5Q/view?usp=sharing
