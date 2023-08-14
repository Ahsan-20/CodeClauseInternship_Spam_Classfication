# Spam Classifier Project

This project was completed as part of my internship at CodeClause. The goal of this project was to develop a spam classifier using Python and Natural Language Processing (NLP) techniques. The classifier is designed to predict whether a given text message is spam or not.

## Project Overview

The project involves the following steps:

1. **Data Collection and Preparation**:
   - The SMS Spam Collection dataset was used for this project, which contains labeled spam and ham messages.
   - The dataset was loaded and preprocessed to prepare it for training and testing.

2. **Data Preprocessing**:
   - The text data underwent preprocessing steps such as tokenization, removal of stopwords, and converting text to lowercase.
   - The processed data was split into training and testing sets.

3. **Training the Classifier**:
   - A Multinomial Naive Bayes classifier was selected as the machine learning algorithm for this project.
   - The classifier was trained using the training data, which was vectorized using the `CountVectorizer` from scikit-learn.
   - Predictions were made on the test set and evaluated for accuracy.

4. **Using the Classifier**:
   - The trained classifier can be used to predict whether new messages are spam or ham.
   - A simple function, `classify_message`, was implemented to classify new messages.

## Getting Started

To run the spam classifier:

1. Clone this repository to your local machine.
2. Download the SMS Spam Collection dataset from [Kaggle](https://www.kaggle.com/uciml/sms-spam-collection-dataset) and place the CSV file in the project directory.


## Results

The accuracy of the spam classifier on the test set was calculated and the confusion matrix was displayed. Additionally, a sample new message was classified to demonstrate the classifier's usage.

