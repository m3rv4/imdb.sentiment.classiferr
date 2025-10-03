# IMDB Sentiment Classification

This project trains a simple machine learning model to classify IMDB movie reviews into **positive** or **negative** categories.

## Dataset
- Source: [IMDB Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- Two categories: `positive`, `negative`
- Preprocessed with text cleaning (lowercasing, removing punctuation, stopwords, etc.)

## Features
- Data loading and preprocessing
- Exploratory analysis (basic statistics)
- Training with **TF-IDF + Logistic Regression**
- Evaluation with accuracy, precision, recall, and F1-score
- A simple **prediction function** where the user can input a sentence and get the predicted category

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/username/imdb-sentiment-classifier.git
   cd imdb-sentiment-classifier
