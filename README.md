# Extractive-summarization
# TF-IDF Based Text Summarizer

This is a basic extractive text summarization tool built using Python and TF-IDF. It processes a longer piece of text and selects the most relevant sentences to generate a concise summary.

## How It Works

1. The input text is split into individual sentences.
2. Each sentence is cleaned and preprocessed (stopwords removed, stemming applied).
3. Sentences are converted into TF-IDF vectors.
4. Sentences are scored based on the sum of their TF-IDF weights.
5. The top N highest-scoring sentences are selected to form the summary.

## Features

- Simple and easy to understand
- Uses NLTK for text preprocessing
- No external datasets needed — just works on any input text
- Saves preprocessed data and vectorizer for reuse
- Includes a basic precision/recall evaluation for testing

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
