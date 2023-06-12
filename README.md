# Fake-News-NLP-Classification
A classification project to test the efficiency of four different classifiers in an NLP model for detecting text-based fake news.

## Comparative Analysis of Four Classifiers for Discerning Authenticity in News Articles
The intentional dissemination of false information poses a significant danger to human society by exacerbating pre-existing tensions, deepening socioeconomic inequalities, and fueling physical violence. Given the intricacies and complexities of human language, training and evaluating machine learning models for classification tasks, such as identifying fake news, are among the most challenging endeavors. In this project, we aim to construct and evaluate a model capable of predicting fabricated news articles using this accessible [kaggle dataset](https://www.kaggle.com/competitions/fake-news/overview).

The models included in the code are:
1. Passive Aggressive Classifier
2. Linear Suport Vector Machine
3. Linear Regression Model
4. Naive-Bayes Classification

## Inference
Though, at first glance, it may appear that Naive Bayes received the lowest accuracy score, despite it being known for its simplicity, efficiency, and effectiveness in handling high-dimensional data. It must be noted that even though Naive Bayes was only 70% accurate, its recall and precision scores were excellent, meaning that it could correctly classify values in either class. However, the most consistently high-performing model was the linear kernel Support Vector Machine which scored in the high 90s across all three categories: Precision, recall and f1-score. It is also worth noting that the performance of these classifiers could still vary greatly depending upon the stop words chosen, features filtered and hyper parameters entered. There is also little guarantee these methods would be effective on non-English language classification problems. However, this experiment determined that a Support Vector Machine is the most effective classifier for addressing an English language fake news detection problem.
