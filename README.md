# Sentiment Analysis and Prediction using LSTM

This project implements a sentiment analysis model using LSTM (Long Short-Term Memory) networks to classify movie reviews as positive or negative. The model is trained on textual data using word embeddings and is capable of predicting sentiment for new reviews.

## Features

- Tokenization and padding of text data

- Deep Learning Model which Uses an LSTM network

- Binary Classification: Outputs either positive or negative sentiment

- A Gradio-based UI for real-time sentiment prediction

## Installation

Ensure you have the required dependencies installed:

`pip install tensorflow scikit-learn joblib pandas numpy`

## Dataset

The dataset used in this project is the IMDb Dataset of 50K Movie Reviews, available on Kaggle. It consists of 50,000 movie reviews labeled as positive or negative.

## Usage

1. Clone the repository

```
git clone https://github.com/sewkani-manya/LSTM_sentiment_analysis.git
cd LSTM_sentiment_analysis
```

2. Download the IMDb dataset from Kaggle and place it in the project directory.

3. Train the model using model.fit()

4. Save the model and tokenizer

5. Load the model for future use

6. Predict sentiment for new reviews


