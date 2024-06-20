# Plagiarism Analyzer

This repository contains a basic and advanced model for analyzing plagiarism in text documents. The models use Natural Language Processing (NLP) techniques to compare text files and identify similarities, making it easier to detect potential plagiarism.

## Basic Model

The basic model utilizes TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity to compare text documents.

### Features

- Reads `.txt` files in the directory
- Vectorizes the text using `TfidfVectorizer`
- Computes cosine similarity between documents
- Outputs similarity scores for each document pair


## Advanced Model

The advanced model offers more sophisticated text processing and analysis features using NLP techniques.

### Features

- Text preprocessing: tokenization, normalization, stemming, and lemmatization
- Vocabulary and frequency analysis
- Regular expression search
- Bag of Words model creation
- Naive Bayes classifier for text classification


## License

This project is licensed under the MIT License.
