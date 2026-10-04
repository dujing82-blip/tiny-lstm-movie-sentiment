# Tiny LSTM Movie Sentiment Analysis 🎬

A simple, teen-friendly TensorFlow/Keras project for learning how an LSTM can classify movie-review sentiment.

## Learning path

**words → word IDs → Embedding → LSTM → positive/negative probability**

Students will:
- load the Keras IMDB movie-review dataset;
- inspect how words are represented as integer IDs;
- pad variable-length reviews to 200 tokens;
- train a small `Embedding(10000, 32) → LSTM(32) → Dense(1)` model;
- evaluate sentiment on real IMDB reviews;
- type their own reviews in an interactive Colab widget;
- watch sentiment change as a sentence unfolds.

## Open in Colab

https://colab.research.google.com/github/dujing82-blip/tiny-lstm-movie-sentiment/blob/main/LSTM_Movie_Sentiment.ipynb

## Classroom note

The model is intentionally small and readable. The goal is to understand sequence modeling and create a natural bridge from **LSTM** to **word embeddings**, not to build a state-of-the-art sentiment system.
