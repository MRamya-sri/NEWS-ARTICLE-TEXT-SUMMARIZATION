

## News Article Text Summarizer

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Summarization](#summarization)
- [Preprocessing](#preprocessing)
- [Models](#models)
- [Contributing](#contributing)
- [License](#license)

## Introduction
News summarization tool that provides both extractive and abstractive summaries of news articles. Users can input a news article and receive a summary within seconds.

## Features
- Extractive summarization: Selects important sentences from the article.
- Abstractive summarization: Generates a summary with new phrases and language.
- Customizable summary length and word limits.

## Summarization

### Extractive Summarization
Extractive summarization identifies important sentences from the article and compiles them into a summary.

### Abstractive Summarization
Abstractive summarization understands the context and generates a summary with new phrases and language, similar to how a human would summarize content.

## Preprocessing
The `Preprocess` class in `summarize.py` handles text preprocessing:
- Converts text to lowercase
- Tokenizes text into sentences and words
- Removes punctuation and stopwords
- Lemmatizes words

## Models
The project uses the following models and techniques:
- T5 model fine-tuned for abstractive summarization
- Word2Vec and GloVe models for word embeddings
- ROUGE metrics for evaluation


## clone
git clone https://github.com/MRamya-sri/highlights.git

## Installation
To install the necessary dependencies, run:
```bash
pip install streamlit pandas altair numpy Pillow nltk transformers wordcloud matplotlib gensim rouge-score
## Make sure to download the NLTK WordNet corpus:
import nltk
nltk.download('wordnet')

## RESULTS


![Screenshot (502)](https://github.com/user-attachments/assets/9623b5c9-c004-4456-ab34-6d513a6b2243)
![Screenshot (501)](https://github.com/user-attachments/assets/21270b6c-0a0f-41a9-960c-6aa4ae2f2e58)
![Screenshot (504)](https://github.com/user-attachments/assets/d9d264dd-44f8-49b8-bc00-6295d7bc7ef8)
