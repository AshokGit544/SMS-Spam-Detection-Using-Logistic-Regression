# SMS Spam Detection Using Logistic Regression

This project is a simple text classification example that checks whether a message is spam or not spam.

The idea is to take short SMS-like messages, convert the words into numbers, train a classification model, and then use that model to predict whether a new message looks like spam.

## Project overview

The project uses:

- sample SMS-style text messages
- labels for spam and not spam
- CountVectorizer for text-to-number conversion
- Logistic Regression for classification

## What this project does

- takes text messages as input
- converts the text into numerical features
- trains a model on labeled messages
- predicts whether a message is spam or not spam
- shows the accuracy of the model

## Why this project is useful

This project is useful for understanding the basics of text classification.

It shows how machine learning can work with text data and how common spam words can help a model identify unwanted messages.

## Tools used

- Python
- NumPy
- scikit-learn

## Workflow

1. Create sample messages
2. Label them as spam or not spam
3. Convert text into numbers using CountVectorizer
4. Train Logistic Regression
5. Test the model
6. Predict a new message

## Output

This project gives:

- model accuracy
- spam or not spam prediction for a new message

## What can be learned from this project

- how text is converted into numbers
- how classification works
- how Logistic Regression can be used for spam detection
- how a model predicts labels for new text

## How to run

1. Open the code in Google Colab or Jupyter Notebook
2. Run the code
3. Check the printed accuracy
4. See the prediction for the new message

## Project goal

The goal of this project is to understand the basic workflow of spam detection using machine learning.
