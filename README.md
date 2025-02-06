Disaster Tweet Classification

Project Overview

This project aims to classify tweets related to disasters using Natural Language Processing (NLP) and Machine Learning (ML) techniques. The dataset used contains tweets labeled as either disaster-related (1) or not (0). Various ML models have been implemented and evaluated for classification accuracy.

Dataset

The dataset used for this project is twitter_disaster.csv, which contains tweets with labels indicating whether they are related to a disaster or not.

Dependencies

Ensure the following Python libraries are installed before running the script:

pip install pandas numpy seaborn nltk scikit-learn matplotlib

Project Workflow

Data Loading and Exploration:

Load the dataset using pandas.

Display the shape and structure of the dataset.

Analyze the distribution of target labels.

Data Preprocessing:

Remove stopwords and punctuation.

Tokenize and lemmatize tweets.

Convert text data into numerical form using TF-IDF Vectorizer.

Feature Engineering:

Bi-gram and Tri-gram TF-IDF vectorization.

Splitting data into training and testing sets.

Model Training and Evaluation:

Multinomial Naive Bayes

Passive Aggressive Classifier

Use 10-fold cross-validation for model performance evaluation.

Compute accuracy, precision, recall, specificity, and F1-score.

Model Saving:

Save the best performing model using pickle for future use.

How to Run the Project

Clone the repository or download the script.

Ensure that twitter_disaster.csv is available in the specified location.

Run the script using:

python Project-7.py

The script will display model performance metrics and save the best model as models.pkl.

Output

Visual representation of target distribution and text length analysis.

Performance metrics for each classification model.

Confusion matrices for model predictions.

Saved models for further inference.

A 

