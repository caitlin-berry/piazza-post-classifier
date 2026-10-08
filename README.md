# Piazza Post Classifier | Machine Learning & NLP

**C++ | Machine Learning | Natural Language Processing | Naive Bayes**

## Overview
Developed a machine learning classifier in C++ that predicts the topics of university discussion posts using natural language processing and a simplified Multivariate Bernoulli Naive Bayes model. The program learns from labeled training data and classifies previously unseen posts based on their text content.

The project demonstrates how probabilistic machine learning methods can be applied to text classification without relying on external machine learning frameworks.

## Key Features
- **Supervised Learning:** Trains on labeled discussion posts to learn relationships between words and categories.
- **Text Processing:** Uses a bag-of-words representation that treats each post as a collection of unique words.
- **Naive Bayes Classification:** Applies probabilistic modeling to predict the most likely topic of a post.
- **Unseen Word Handling:** Accounts for words not previously encountered during training.
- **Model Evaluation:** Compares predicted labels against actual labels and reports classification accuracy.

## Technical Highlights
- Implemented a probabilistic text classifier in C++ using standard library data structures.
- Processed CSV datasets containing labeled training and testing examples.
- Used maps and sets to organize vocabulary and track word occurrences across categories.
- Applied log-probabilities to evaluate candidate classifications while improving numerical stability.
- Built a data-driven classification system that learns categories from training examples rather than hardcoding labels.

## Skills Demonstrated
C++, STL, machine learning, natural language processing (NLP), Naive Bayes classification, supervised learning, text processing, probability, CSV parsing, and model evaluation.

## Source Code
This project was completed as part of EECS 280 at the University of Michigan. The implementation is maintained in a private repository to respect course academic integrity policies.
