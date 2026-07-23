# NLP Learning

This repository contains hands-on NLP experiments and tutorials built with Jupyter notebooks. The content is organized to teach core natural language processing concepts, text preprocessing, and word embedding techniques.

## Repository Contents

- `Bag of Words.ipynb`
  - Introduction to the Bag of Words representation for text data.

- `Tokenization Using NLTK.ipynb`
  - Tokenizing text into words and sentences using NLTK.

- `Text Preprocessing-Stopwords With NLTK.ipynb`
  - Removing stopwords and preparing text for NLP models.

- `Stemming And Its Types- Text Preprocessing.ipynb`
  - Demonstrates stemming approaches and explains their impact.

- `TF-IDF.ipynb`
  - Explains term frequency–inverse document frequency for text vectorization.

- `Word Embedding Techniques.ipynb`
  - Compares different word embedding methods and their use cases.

- `Word2Vec Implementation.ipynb`
  - Implements and explores Word2Vec embeddings.

- `POS Tagging and NER.ipynb`
  - Covers part-of-speech tagging and named entity recognition with NLTK/spacy.

## Dataset

- `smsspamcollection/SMSSpamCollection.txt`
  - SMS spam detection dataset used for text classification experiments.

## Setup

1. Create and activate a Python virtual environment.

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install required packages.

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook.

```bash
jupyter notebook
```

## Notes

- The repository uses a `.gitignore` file to exclude local virtual environments, cache files, and generated artifacts from version control.
- Keep notebooks and data separate from environment files for easier collaboration.

## Recommended workflow

1. Activate your virtual environment.
2. Install dependencies.
3. Open the notebook you want to study.
4. Run cells sequentially and experiment with the code.

Enjoy exploring NLP concepts with these interactive notebooks!