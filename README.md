# bert-news-topic-classifier
A Transformer-based NLP project that fine-tunes BERT/DistilBERT on the AG News dataset to classify news headlines into World, Sports, Business, and Sci/Tech categories. The model is evaluated using Accuracy and F1-Score and can be deployed with Streamlit or Gradio for real-time predictions.
# BERT News Topic Classifier

## Overview
This project fine-tunes a Transformer-based model (BERT/DistilBERT) on the AG News dataset to classify news headlines into four categories:

- World
- Sports
- Business
- Sci/Tech

The model is trained using the Hugging Face Transformers library and evaluated using Accuracy and F1-Score.

## Dataset
- AG News Dataset
- Source: Hugging Face Datasets

## Features
- News text preprocessing and tokenization
- Fine-tuning of a pre-trained BERT model
- Multi-class news classification
- Accuracy and F1-Score evaluation
- Real-time prediction support

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Scikit-learn
- Jupyter Notebook

## Model
- bert-base-uncased / distilbert-base-uncased

## Categories
1. World
2. Sports
3. Business
4. Sci/Tech

## Results
The model successfully classifies news headlines into their respective categories and is evaluated using standard classification metrics.

