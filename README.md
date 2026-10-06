# NLP Text Classification - Spam Detection

## Project Overview

This project builds an NLP-based Spam Message Classification System using TF-IDF and Logistic Regression.

## Workflow

Dataset
↓
Text Cleaning
↓
Tokenization
↓
TF-IDF Feature Extraction
↓
Train/Test Split
↓
Machine Learning Model
↓
Prediction
↓
Evaluation

## Dataset

The dataset contains SMS-style messages classified into:

- Spam
- Not Spam

## Text Preprocessing

The text is cleaned by:

- Converting text to lowercase
- Removing special characters
- Splitting text into words

## Feature Extraction

TF-IDF is used to convert text into numerical feature vectors.

## Machine Learning Model

Logistic Regression is used for classification.

## Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Model Files

The trained classifier is saved as:

`spam_classifier.pkl`

The TF-IDF vectorizer is saved as:

`tfidf_vectorizer.pkl`

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Logistic Regression

## Sample Prediction

The system can classify new messages as Spam or Not Spam.

## Project Objective

The objective is to understand how raw text can be cleaned, converted into numerical representations using TF-IDF, and used to build a practical NLP classification system.