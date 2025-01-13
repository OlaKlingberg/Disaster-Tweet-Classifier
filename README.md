# Disaster Tweet Classifier

## Background
This project was made for Module 4 of the course *Introduction to Deep Learning* (DTSA-5511) at University of Colorado Boulder. The task was based on the Kaggle competition [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started).

## Description
The project demonstrates the use of machine-learning models to **classify tweets as disaster-related or not**. The models explored are **LSTM** and **DistilBERT**. The performance is evaluated using K-fold cross-validation. Metrics such a precision, recall, and F1-score are plotted.

## Data source
The dataset can be accessed from the page for the Kaggle competition [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/data).

## Key highlights:
* Implementation of **LSTM** and **DistilBERT** architectures for binary classification.
* Handling **imbalanced datasets** with class weights.
* **Custom callbacks for tracking metrics** and visualization of model performance.
* Comparative analysis of model architectures.

This project showcases practical skills in natural language processing (NLP) and model evaluation, relevant for tasks in text classification and social media analysis.

## Results
The model that achieved the best F1 validation score (0.7903) was a DistilBERT model with a learning rate of $1 \times 10^5$.
