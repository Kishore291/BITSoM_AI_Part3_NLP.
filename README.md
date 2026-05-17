# NLP Sequence Modeling (Customer Sentiment)

## Overview
This repository contains Part 3 of the AI Solution Design project. The objective is to build a Natural Language Processing (NLP) pipeline to classify customer text messages into sentiment categories (Positive, Negative, Neutral).

## Technical Stack
* **Data Processing:** Pandas, NumPy, NLTK (Stopwords removal, Text cleaning)
* **Text Vectorization:** Scikit-Learn (TF-IDF)
* **Baseline Modeling:** Scikit-Learn (Logistic Regression)
* **Deep Learning:** TensorFlow / Keras (LSTM Neural Network, Word Embeddings, Sequence Padding)

## Repository Structure
* `notebook.ipynb`: The complete code for data exploration, text preprocessing, baseline modeling, and the LSTM network.
* `requirements.txt`: The required Python libraries to run the environment.
* `results/model_evaluation.csv`: The final Loss and Accuracy metrics of the LSTM model.
* `results/sample_predictions.txt`: A sample of true vs. predicted sentiment labels from the test set.
