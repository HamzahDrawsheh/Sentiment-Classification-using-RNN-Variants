# Sentiment Classification using RNN Variants

This project implements and compares multiple deep learning models for **sentiment analysis** on the IMDb movie reviews dataset.

## Objective
To classify movie reviews as **positive** or **negative** using different recurrent neural network architectures and analyze their performance.

## Dataset
- IMDb Movie Reviews Dataset
- Loaded using the HuggingFace `datasets` library
- Binary sentiment labels (positive / negative)

## Models Implemented
- Simple RNN
- LSTM
- Bi-directional LSTM (BiLSTM)
- Multi-layer LSTM

## Preprocessing Steps
- Tokenization using NLTK
- Stopword removal
- Vocabulary creation
- Sequence padding
- Train / test split

## Technologies Used
- Python
- PyTorch
- HuggingFace Datasets
- NLTK
- NumPy

## How to Run
1. Install dependencies:
```bash
pip install torch datasets nltk
