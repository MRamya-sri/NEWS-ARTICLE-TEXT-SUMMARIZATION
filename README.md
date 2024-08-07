

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

## RESULTS

![Screenshot (502)](https://github.com/user-attachments/assets/e08c2df1-2b4c-4463-a96f-7f85738624d6)
![Screenshot (501)](https://github.com/user-attachments/assets/cc1a23de-c55a-44a8-8785-9285fc7fd7f7)
![Screenshot (504)](https://github.com/user-attachments/assets/c50122c6-d554-4fb8-801d-0399bdaafb89)

## clone
git clone https://github.com/MRamya-sri/NEWS-ARTICLE-TEXT-SUMMARIZATION.git

## Installation
To install the necessary dependencies, run:
```bash
pip install streamlit pandas altair numpy Pillow nltk transformers wordcloud matplotlib gensim rouge-score
## Make sure to download the NLTK WordNet corpus:
import nltk
nltk.download('wordnet')




