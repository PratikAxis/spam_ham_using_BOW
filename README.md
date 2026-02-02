# Spam Message Classification using Bag of Words
## Overview

This mini project implements a Spam Message Classifier using the Bag of Words (BoW) technique in Natural Language Processing. The model classifies SMS messages as Spam or Not Spam (Ham) based on word frequency features.

## Objective

To understand how textual data can be converted into numerical features using Bag of Words and used with a machine learning classifier for text classification.

## Dataset

SMS Spam Collection Dataset

## Labels:

0 → Spam

1 → Not Spam (Ham)

## Methodology

Load and preprocess SMS text data --> Convert text into numerical vectors using CountVectorizer (BoW) --> Split data into training and testing sets --> Train a Multinomial Naive Bayes classifier --> Evaluate model performance and test custom messages

## Technologies Used

### Python

### Pandas, NumPy

### scikit-learn

### NLP (Bag of Words)

## Result

    The model achieves high accuracy (~95%+) on unseen data and correctly classifies spam and non-spam messages.

### Key Learning Outcomes

### Text preprocessing and feature extraction

### Working of Bag of Words

### Applying Naive Bayes for text classification

### Understanding limitations of BoW

## Future Improvements

### Use TF-IDF instead of BoW

### Add bigram features

### Deploy using Streamlit
