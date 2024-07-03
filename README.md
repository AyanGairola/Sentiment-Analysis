# Sentiment Analysis with RNN
This project implements a simple sentiment analysis model using a Recurrent Neural Network (RNN) on the IMDB movie review dataset.
## Overview
The project uses TensorFlow and Keras to build and train an RNN model for binary sentiment classification (positive/negative) on movie reviews. It demonstrates:

Loading and preprocessing the IMDB dataset
Building a simple RNN model
Training and evaluating the model

## Requirements

Python 3.11+
TensorFlow 2.16+
Keras 3.3+

## Usage
The main code is contained in the Jupyter notebook Sentiment-Analysis.ipynb. To run:

Ensure you have the required dependencies installed
Open and run the notebook cells sequentially

## Model Architecture
The model consists of:

A SimpleRNN layer with 32 units
A Dense output layer with sigmoid activation for binary classification


## Future Work
### Potential areas for improvement:

Increase model complexity (e.g. add more layers, use LSTM/GRU)
Experiment with different hyperparameters
Implement word embeddings
Try more advanced preprocessing techniques
