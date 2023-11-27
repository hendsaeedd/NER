# NER
# Named Entity Recognition (NER) Project

This project is a Named Entity Recognition (NER) tool implemented in Python using the Natural Language Toolkit (NLTK) library. It includes functionalities for data preprocessing, statistical analysis, and part-of-speech tagging.

## Introduction

Named Entity Recognition (NER) is a natural language processing (NLP) task that involves identifying and classifying named entities (e.g., persons, organizations, locations) in text. This project provides a set of tools for processing and analyzing text data with a focus on NER.

## Dataset
The project uses the NER dataset located in the NERdataset folder. The dataset is loaded from a CSV file (NER-dataset.csv) and processed for analysis.

## Preprocessing
The dataset undergoes several preprocessing steps, including lowercasing, tokenization, stopword removal, punctuation removal, and lemmatization or stemming.

## N-grams
N-grams are generated from the words in the dataset, providing insight into the local context of words.

## Part-of-Speech (POS) Tagging
The project includes POS tagging using the NLTK library. It helps identify the grammatical parts of words in the dataset.

## Stemming and Lemmatization
Both stemming and lemmatization are applied to reduce words to their base or root form, aiding in feature reduction and normalization.

