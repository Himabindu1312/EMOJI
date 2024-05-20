## Emoji-Based Sentiment Analysis with LSTM

## Description:
This project implements a sentiment analysis model using emojis as labels and a Long Short-Term Memory (LSTM) neural network architecture. The dataset comprises text samples paired with corresponding emojis. The script processes the text data, converts it into word embeddings using pre-trained GloVe vectors, and trains an LSTM model to predict the sentiment conveyed by the text. The model is trained and evaluated using accuracy metrics. Finally, the trained model is employed to predict sentiments for new text samples.

## Key Features:

Utilizes the Emoji package to represent sentiments with emojis.
Implements LSTM architecture for sentiment analysis.
Pre-processes text data and converts it into word embeddings.
Trains the model and evaluates its performance using accuracy.
Predicts sentiments for new text samples.

## Usage:

Install the necessary dependencies, including the Emoji package (pip install emoji).
Load the dataset and preprocess the text data.
Train the LSTM model using the processed text data.
Evaluate the model's performance using accuracy metrics.
Use the trained model to predict sentiments for new text samples.

## Requirements:

Python 3.x
Emoji
NumPy
Pandas
scikit-learn
TensorFlow/Keras

## Dataset:
The dataset consists of text samples paired with corresponding emojis. Each text sample represents a sentence or phrase, and each emoji represents the sentiment expressed in the text.
