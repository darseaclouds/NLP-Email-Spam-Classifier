# NLP-Email-Spam-Classifier
Originally coded in PyCharm, transferred to Colab

This program classifies emails as either spam or non-spam (ham).

It uses the data from https://www.kaggle.com/datatattle/email-classification-nlp
To preprocess the data, it uses nltk and regex.
The program generates 7 different classifiers from sklearn: "K Nearest Neighbors", "Decision Tree", "Random Forest", "Logistic Regression", "SGD Classifier", "Naive Bayes", "SVM Linear."
It then creates a voting classifier from the top 5 performing models and displays a confusion matrix with the results.
