[:uk: Go to english version](https://github.com/iseka-dev/sentiment-analysis/blob/master/README.md)

# Análisis de sentimiento en críticas de cine

El objetivo de este proyecto es desarrollar un modelo que permita identificar la valoración de *críticas de cine* en *positivas* y *negativas*.

En el notebook [SentimentAnalysis.ipynb](https://github.com/iseka-dev/sentiment-analysis/blob/master/SentimentAnalysis.ipynb) se puede encontrar el dataset cargado junto a los modelos entrenados y evaluados. 

En el notebook [deployment.ipynb](https://github.com/iseka-dev/sentiment-analysis/blob/master/deployment.ipynb) se encuentra la puesta en producción del modelo. El mismo es cargado en IBM Cloud y a través de la API accedemos a él para realizar predicciones.

Herramientas: SupportVectorMachines (SVC), tfidfVEctorizer, RandomForestClassifier, Multilayer Perceptron (MLPClassifier), AdaBoost, VotingClassifier, ROC-AUC score, IBM Cloud, Watson AP

:arrow_right: Este proyecto fue desarrollado como una actividad del curso de DATA SCIENCe de ACAMICA.
