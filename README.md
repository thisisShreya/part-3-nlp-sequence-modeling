# part-3-nlp-sequence-modeling

# NLP and Sequence Modeling Mini Project

## Project Objective

The objective of this project is to build an NLP pipeline and compare traditional text vectorization methods with sequence-based deep learning approaches.

## Dataset Understanding

The dataset contains text records and target labels used for NLP classification tasks.

Analysis included:
- Number of records
- Target classes
- Sample text records
- Average text length
- Class distribution

## Text Preprocessing

The following preprocessing steps were performed:
- Lowercasing
- Removing special characters
- Tokenization
- Sequence padding

## Text Vectorization

TF-IDF vectorization and tokenizer-based sequences were used.

Text must be converted into numerical vectors because machine learning and neural networks cannot process raw text directly.

## Baseline Model

A Logistic Regression model with TF-IDF vectorization was used as the baseline model.

Evaluation metrics:
- Accuracy
- Classification Report
- Confusion Matrix

## Sequence Model

An LSTM sequence model was implemented.

Architecture:
- Embedding Layer
- LSTM Layer
- Dense Output Layer

Loss Function:
- Binary Crossentropy

Evaluation Metric:
- Accuracy

## Attention and Transformer Reflection

### Why RNNs struggle with long-term dependencies

RNNs gradually forget older information while processing long sequences.

### How LSTMs help

LSTMs use memory cells and gates to preserve important information for longer durations.

### What attention solves

Attention helps models focus on the most relevant words in a sequence.

### Why transformers are important

Transformers process text more efficiently and power modern Generative AI systems such as large language models.

## Libraries Used

- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset Source

Dataset provided in assignment Google Drive link.
