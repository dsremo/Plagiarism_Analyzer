# Plagiarism Analyzer

This repository contains a basic and advanced model for analyzing plagiarism in text documents. The models use Natural Language Processing (NLP) techniques to compare text files and identify similarities, making it easier to detect potential plagiarism.

## Basic Model

The basic model utilizes TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity to compare text documents.

### Features

- Reads `.txt` files in the directory
- Vectorizes the text using `TfidfVectorizer`
- Computes cosine similarity between documents
- Outputs similarity scores for each document pair

### Usage

1. Place your `.txt` files in the project directory.
2. Run the script to check for plagiarism:
    ```bash
    python basic_model.py
    ```

## Advanced Model

The advanced model offers more sophisticated text processing and analysis features using NLP techniques.

### Features

- Text preprocessing: tokenization, normalization, stemming, and lemmatization
- Vocabulary and frequency analysis
- Regular expression search
- Bag of Words model creation
- Naive Bayes classifier for text classification

### Usage

1. Ensure your data file (`train_snli.txt`) is in the project directory.
2. Run the script for advanced text analysis:
    ```bash
    python advanced_model.py
    ```

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/plagiarism-analyzer.git
    cd plagiarism-analyzer
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## License

This project is licensed under the MIT License.
