# MiniProjet_TwitterSentimentAnalysis

Dernier délai : 18 Décembre 2023

## Sujet : analyse de sentiments

Le traitement automatique de la langue est un domaine multidisciplinaire impliquant la linguistique, l'informatique et l'intelligence artificielle. Il vise à créer des outils de traitement de la langue naturelle pour diverses applications. Parmi ces applications, nous pouvons citer celles qui relèvent du traitement des réseaux sociaux. Les sites de médias sociaux, tels que Twitter, sont une source riche de nombreux types d'informations, notamment en matière de santé. Ce projet consiste à développer des modèles de classification des sentiments (positive, negative ou neutre) sur les réseaux sociaux avec trois architectures différentes (LSTM, BERT, et GPT), et à évaluer le meilleur d’entre eux.

Dataset est le site Kaggle: training.1600000.processed.noemoticon.csv

## Prerequisite

- 

# LSTM

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fanthommm/MiniProjet_TwitterSentimentAnalysis/blob/main/miniprojet_lstm_deep_learning.ipynb)

## Overview
1) *Import et load dataset*
2) *Data processing*
    1) *Tokenization*
    2) *Padding*
    3) *Data splitting*
    4) *Encoder*
7) *Embedding*
8) *Modeling*
9) *Evaluation*


# BERT

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fanthommm/MiniProjet_TwitterSentimentAnalysis/blob/main/Sentiments_Analysis_with_BERT_Model.ipynb)

This notebook contains the code for a sentiment analysis model using BERT (Bidirectional Encoder Representations from Transformers). The model is trained on a dataset for sentiment classification.

## Overview

1) Data preparing 
2) Tokenization
3) Model Training ( a small version of BERT Model  for sequenceClassificaton )
4) Evaluation (accuracy = 0.97 , loss = 0.10)
5) Interference / predictions
