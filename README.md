# nlp_quora_duplicate_questions

# Identifying duplicate questions

Over 100 million people visit Quora every month, and many people ask similar (or the same) questions. Various questions with the same intent can cause people to spend extra time searching for the best answer to their question, and results in members answering multiple versions of the same question. 

The goal of this project is to identify whether two questions are duplicates or not (binary classification problem).

## Data

Quora dataset that contains about 400K pairs of questions ('question1' and 'question2') and labels for each pair (column 'is_duplicate').

## Project

1. Data analysis (quora_data_analysis.ipynb)
2. Data preprocessing and building a Keras model to predict whether two questions are duplicates (quora_model.ipynb)
