# Hashtag-Based-Reel-Classification
This project focuses on classifying Instagram reels into topical categories based solely on their hashtags using traditional machine learning techniques (no deep learning). The goal is to explore how much information hashtags alone can reveal about the content category of a reel.

Dataset
File: cleaned_reels_hashtags.csv

Columns include:

hashtags - Raw hashtags extracted from reels

lemmatized_tags - Preprocessed, cleaned, and lemmatized version of hashtags

topic - The manually or semi-automatically labeled category (target)

encoded_topic - Numeric encoding of the category

Objective
To classify reels into one of several topics (such as Sports, Food, Comedy, Fashion) using only their hashtags. The project avoids deep learning models to remain within the scope of traditional machine learning.

ML Approach
Text Vectorization: TF-IDF with uni-grams and bi-grams
Model Used: Logistic Regression with class weights to address imbalance
Pipeline: Built using scikit-learn for seamless preprocessing and modeling
Evaluation: Classification report (Precision, Recall, F1-Score), Confusion Matrix

Features
Cleaned and lemmatized text input

Handles class imbalance

Scikit-learn pipeline for reproducibility

Easy to extend or replace with additional classifiers

Results
Model evaluation was done using an 80/20 train-test split. Performance metrics include:

Accuracy: (insert final accuracy here)
Precision, Recall, and F1-Score are provided per class in the classification report.
A confusion matrix is used to visualize class-wise errors.

Requirements
Python 3.x
Libraries: pandas, scikit-learn, nltk, matplotlib, seaborn, spacy

How to Run
Clone the repository

Install the required packages

Run the notebook Hashtag-Based Reel Classification.ipynb

Modify or experiment with additional models as needed

Author
Sumi Chatterjee
