# SMS Spam Detection

This repository contains code and resources for building a SMS spam detection model using the SMS Spam Collection Dataset from UCI Machine Learning Repository. The goal is to develop a machine learning model that can accurately classify incoming SMS messages as either spam or legitimate.

## Dataset

The SMS Spam Collection Dataset is available on Kaggle and can be downloaded from the following link: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset). It consists of a collection of over 5,572 SMS messages, which have been labeled as spam or legitimate.

The dataset contains foloowing columns:

- v1	
- v2	
- Unnamed: 2	
- Unnamed: 3	
- Unnamed: 4

## Dependencies

- Python 3
- pandas
- scikit-learn
- matplotlib
- seaborn
- nltk
- string
- wordCloud
- collections

## Vectorizers Used

To convert the text messages into numerical representations, two vectorization techniques have been employed:

- CountVectorizer

- TfidfVectorizer

## Models Used

In this project, three variants of Naive Bayes models have been implemented for SMS spam detection:

- Gaussian Naive Bayes (GaussianNB)

- Multinomial Naive Bayes (MultinomialNB)

- Bernoulli Naive Bayes (BernoulliNB)

## Evaluation Results

The precision scores for each model with CountVectorizer and TfidfVectorizer are as follows:

- Precision Score with CountVectorizer:

    - Gaussian Naive Bayes: 0.5185185185185185
    - Multinomial Naive Bayes: 0.8881578947368421
    - Bernoulli Naive Bayes: 0.9661016949152542

- Precision Score with TfidfVectorizer:

    - Gaussian Naive Bayes: 0.5020746887966805
    - Multinomial Naive Bayes: 0.9915966386554622
    - Bernoulli Naive Bayes: 0.9606299212598425

Please note that precision score measures the proportion of correctly predicted positive samples (spam) out of the total predicted positive samples.

## Acknowledgements

- The SMS Spam Collection Dataset was originally compiled and made available by Tiago A. Almeida and José María Gómez Hidalgo on the UCI Machine Learning Repository.