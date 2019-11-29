[:es: Ir a versión en español](https://github.com/iseka-dev/sentiment-analysis/blob/master/README.sp.md)

# Sentiment analysis in film reviews

The purpose of this project is to develop a predictive model to assess and classify film reviews as positive or negative.

The notebook [SentimentAnalysis.ipynb](https://github.com/iseka-dev/sentiment-analysis/blob/master/SentimentAnalysis.ipynb) contains the loaded dataset and trained models.

In the notebook [deployment.ipynb](https://github.com/iseka-dev/sentiment-analysis/blob/master/deployment.ipynb) the model is deployed. It is loaded and stored at the IBM Cloud, so it can be used to predict sentiment in new reviews.

Tools: SVC, tfidfVEctorizer, RandomForestClassifier, Multilayer Perceptron (MLPClassifier), AdaBoost, VotingClassifier, ROC-AUC score, IBM Cloud, Watson AP