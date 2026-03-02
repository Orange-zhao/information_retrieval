# Information Retrieval: Controlled Vocabulary vs. Free Text Search
This project is an implementation of an Information Retrieval (IR) system designed to compare two primary search methodologies: **Controlled Vocabulary** (using predefined taxonomies) and **Free Text Search** (using natural language processing and TF-IDF scoring).

## 🎯 Project Objectives
The goal of this assignment is to demonstrate how structured data organization (Controlled Vocabulary) compares against unstructured search (Free Text) in terms of retrieval precision and recall.

## 🔍 Key Features
- **Controlled Vocabulary Search**: Implements a structured search mechanism using a predefined set of terms. Includes synonym expansion via WordNet to bridge the gap between user queries and the controlled index.
- **Free Text Search**: A flexible search engine that processes natural language queries using:
    - Text Normalization (Tokenization, Stop-word removal, Case folding).
    - TF-IDF Weighting to rank document relevance.
- **Query Expansion**: Automatic expansion of search terms to include variants and related concepts, improving the recall of the search engine.
- **Comparative Analysis**: Evaluates how different indexing methods affect the retrieval of documents related to specific topics (e.g., COVID-19, Omicron variants, etc.).

## 🛠️ Implementation Details
- **Language**: Python (Jupyter Notebook)
- **Core Libraries**: `nltk` (for WordNet and NLP), `inflect` (for number-to-text conversion), `pandas` (for result tabulation).
- **Dataset**: A collection of text documents focused on news and public health.

## 🚀 Getting Started
1. **Prerequisites**: Ensure you have Python installed with `nltk`, `pandas`, and `inflect` libraries.
2. **Dataset Setup**: `.txt` files in the dataset directory.
