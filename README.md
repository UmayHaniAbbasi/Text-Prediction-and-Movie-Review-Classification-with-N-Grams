# Text-Prediction-and-Movie-Review-Classification-with-N-Grams
This repository contains the implementation of text prediction and movie review classification using N-gram models (unigram, bigram, trigram). The goal is to train a language model from scratch on a movie review dataset, which will be used for generating predictions and labeling movie reviews based on their respective classes.

Key Objectives:
Text Prediction Task:

Unigram Model: Predicts the most frequent word in the corpus.

Bigram Model: Predicts the next word based on the previous word.

Trigram Model: Predicts the next word based on the previous two words.

The models will be trained from scratch without using external libraries and will be used to predict the next word in a sequence.

Movie Review Labeling (Classification) Task:

Implements a Bayesian Classification Function to suggest labels for the generated movie reviews based on their content.

The unigram, bigram, and trigram models are used to process the movie reviews, and the function will predict labels (e.g., positive or negative reviews) using the models.

Evaluates the classification accuracy using standard metrics like precision, recall, and F1 score.

Tasks and Deliverables:
Data Preparation:

Read a text corpus (movie reviews dataset) from a file.

Preprocess the text by converting it to lowercase and removing punctuation.

Model Building:

Implement unigram, bigram, and trigram models for text prediction.

Prediction Function:

Implement a function to predict the next word based on the previous word(s) for unigram, bigram, and trigram models.

Movie Review Labeling:

Implement the classification of generated movie reviews based on trained models (unigram, bigram, trigram) and suggest appropriate labels.

Evaluation:

Use standard classification metrics to evaluate the performance of the labeling function.

The repository will include:

Code for building unigram, bigram, and trigram models.

A Bayesian classification function to label movie reviews.

Data preprocessing scripts.

Evaluation metrics (accuracy, precision, recall, and F1 score).
