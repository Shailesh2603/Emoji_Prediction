# Emoji Predictor using LSTM

This project builds a machine learning model using Long Short-Term Memory(LSTM) that predicts the most likely emoji based on the text of a social media post.

## Overview

- Task: Predict emoji based on the social media posts in the dataset.
- Dataset: Twitter emoji predictio datdaset from kaggle.com .
- Model: LSTM-based neural network using TensorFlow/Keras.

## Files

- `Train.csv`: Training dataset.
- `Test.csv`: Test dataset.
- `Mapping.csv`: Maps emoji IDs to emoji characters.
- `Emoji_Predict.ipynb`: Jupyter notebook with complete code.
- `predictions.csv`: Output file containing predictions for the test set.
- `emoji_pred_model.keras`: Saved trained model.
- `toke.pkl`: Saved tokenizer.
- `prep.pkl`: Preprocessing details like `maxlen` and emoji mapping.

## Requirements

- Python 3.0
- TensorFlow
- Pandas
- Numpy
- scikit-learn
