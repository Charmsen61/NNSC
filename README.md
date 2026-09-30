# NNSC
Neural Network Sentiment Classifier with PyTorch
# Simple PyTorch Sentiment Classifier

This is a small sentiment analysis project built with PyTorch.  
It uses a tiny custom dataset and a basic neural network to classify text as
positive or negative.

## Features
- Tokenization and vocabulary building
- Padding for fixed-length input
- Embedding layer + mean pooling
- Simple feed‑forward classifier
- Training loop and prediction function

## How to Run
1. Install PyTorch:
   pip install torch

2. Run the script:
   python sentiment.py

## Example
predict_sentiment("I love this", model, vocab, max_length)

Output:
Positive or Negative + probability scores.

## Notes
This is a simple demo project.  
Small dataset, limited vocabulary, not for real production use.
