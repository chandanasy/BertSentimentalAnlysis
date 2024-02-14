# Sentimental Analysis with BERT

## Introduction
This project focuses on the sentiment analysis of movie reviews using the BERT (Bidirectional Encoder Representations from Transformers) model. BERT has been a transformative force in the field of natural language processing (NLP), providing a new architecture for pre-training language representations. For detailed information about BERT, refer to the original paper [here](https://arxiv.org/abs/1810.04805).

The goal is to classify movie reviews into positive or negative sentiments based on their content. We utilize the [Huggingface transformers library](https://github.com/huggingface/transformers), which offers an extensive collection of pre-trained models, to obtain text embeddings from BERT. We then feed these embeddings into a Recurrent Neural Network (RNN) model to perform the final sentiment classification.

## Project Components

- `bert_sentiment_analysis.ipynb`: The Jupyter notebook containing the entire analysis workflow, including data preprocessing, model training, and evaluation.


## Setup and Installation

Before running the project, ensure that you have Python installed on your system. This project is developed using Python 3.8, and compatibility with previous versions is not guaranteed.

