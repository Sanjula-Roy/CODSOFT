# 🎬 Movie Genre Classification

## Overview

This project predicts the genre of a movie based on its plot summary using Natural Language Processing (NLP) and Machine Learning techniques.

The IMDb Genre Classification Dataset was used to train and evaluate multiple machine learning models. Movie descriptions were converted into numerical features using TF-IDF Vectorization and classified using different algorithms.

## Dataset

* Source: IMDb Genre Classification Dataset (Kaggle)
* Total Records: 54,214 movies
* Features:

  * ID
  * Movie Title
  * Genre
  * Description

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Joblib

## Machine Learning Workflow

1. Data Loading and Exploration
2. Data Preprocessing
3. TF-IDF Vectorization
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Model Comparison
8. Model Saving

## Models Implemented

### Logistic Regression

Accuracy: 57.99%

### Naive Bayes

Accuracy: 52.25%

### Support Vector Machine (SVM)

Accuracy: 56.95%

## Model Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 57.99%   |
| SVM                 | 56.95%   |
| Naive Bayes         | 52.25%   |

## Best Model

Logistic Regression achieved the highest accuracy and was selected as the final model.

## Files Included

* Movie_Genre_Classification.ipynb
* movie_genre_model.pkl
* tfidf_vectorizer.pkl
* README.md

## Conclusion

This project successfully classifies movie genres using textual plot summaries. Among the three machine learning algorithms tested, Logistic Regression produced the best performance and was selected as the final prediction model.
