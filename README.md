# -Fake-News-Classifier-Using-Bidirectional-LSTM
The Fake News Classifier is a deep learning-based project that uses a Bidirectional Long Short-Term Memory (Bi-LSTM) network to classify news articles as either real or fake. With the rise of misinformation, accurately identifying fake news is crucial for ensuring the credibility of information on digital platforms. This model processes textual data to detect patterns that help distinguish between real and fabricated content.

Table of Contents
Project Overview
Dataset
Model Architecture
Installation
Usage
Results
Future Improvements
Contributing
License
Dataset
For this project, the dataset used is from Kaggle's Fake News Dataset which contains labeled news articles. The dataset consists of the following columns:

Title: The title of the news article.
Text: The full body of the news article.
Label: Binary classification (1: Fake, 0: Real).
The dataset can be downloaded from Kaggle.

Model Architecture
The classifier is built using Bidirectional LSTM (Bi-LSTM), a deep learning model effective for text-based tasks:

Embedding Layer: Converts text input into dense vectors of fixed size.
Bidirectional LSTM: Captures long-term dependencies in both forward and backward directions to understand context better.
Dropout: Helps prevent overfitting during training.
Dense Output Layer: The final layer with a sigmoid activation function to predict probabilities for binary classification.
Hyperparameters:
Embedding size: 100
LSTM units: 128
Dropout rate: 0.3
Optimizer: RMSprop
Loss function: Binary Cross-Entropy
