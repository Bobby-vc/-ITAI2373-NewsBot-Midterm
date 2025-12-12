ITAI2373 — NewsBot Intelligence System
Midterm Project — Machine Learning Text Classification

This project demonstrates the development of a NewsBot Intelligence System using machine learning and natural language processing. The goal of this system is to classify BBC news articles into categories using different text-representation methods and compare performance across models.

Kaggle BBC News Dataset [https://www.kaggle.com/datasets/gpreda/bbc-news]

Project Objectives

- Load and preprocess the BBC News dataset

- Build multiple text representation models:

- Bag-of-Words (BOW)

- TF-IDF

- Word Embeddings

- Train and evaluate classification models

- Compare performance between representations

- Generate visualizations and performance metrics

- Produce insights for the NewsBot system



Key Analyses Performed

- Preprocessing

- Tokenization

- Stopword removal

- Lowercasing

- Lemmatization

- Feature Extraction

- BOW vectors using CountVectorizer

- TF-IDF vectors

- Dense embedding representations

- Models Tested

- Logistic Regression

- Support Vector Machine

- Random Forest

- Naïve Bayes

- Evaluation Metrics

- Accuracy

- F1 Score

- Confusion Matrix

- Classification Report

- Visualization Outputs

- Term frequency charts

- Category distribution

- Training accuracy curves



My Contributions

- Full preprocessing pipeline development

- Implementation of TF-IDF & BOW feature extraction

- Hyperparameter tuning for classifier models

- Visualizations (matplotlib/seaborn)

- Summary interpretation of results

- Integration of models into a unified evaluation framework

- Documentation and notebook cleanup



Findings & Insights

- TF-IDF outperformed BOW in most models due to better handling of term relevance.

- SVM achieved the highest accuracy, indicating strong performance on sparse text data.

- Word embeddings improved semantic understanding, but required more compute.

- Errors occurred primarily in similar categories (e.g., politics vs. business).



How This Supports the NewsBot System

- Enables automatic article classification

- Helps direct news content to appropriate channels

- Improves search accuracy by labeling articles

- Can be extended to recommendation systems
