# Fake News Detection using NLP and Machine Learning

## Project Overview

This project focuses on detecting fake news articles using Natural Language Processing (NLP) and Machine Learning techniques. The system classifies news articles as REAL or FAKE based on textual content analysis.

The project uses text preprocessing, TF-IDF vectorization, and multiple machine learning algorithms to build an accurate news classification model.

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLP Techniques
- Jupyter Notebook

---

# Machine Learning Algorithms Used

The following machine learning algorithms were implemented and compared:

1. Logistic Regression
2. Naive Bayes
3. Random Forest Classifier

---

# NLP Techniques Used

- Text Cleaning
- Lowercase Conversion
- Punctuation Removal
- URL Removal
- Number Removal
- TF-IDF Vectorization

---

# Dataset Information

Dataset Source:
- Fake and Real News Dataset (Kaggle)

Dataset Files:
- Fake.csv
- True.csv

Features Used:
- News Article Text

Target Labels:
- REAL
- FAKE

---

# Project Workflow

## 1. Importing Libraries
Imported Python libraries required for NLP, data processing, visualization, and machine learning.

## 2. Loading Dataset
Loaded and combined fake and real news datasets into a single DataFrame.

## 3. Data Cleaning
Performed text preprocessing using regular expressions and string operations.

## 4. Data Preprocessing
Separated features and labels and split the dataset into training and testing sets.

## 5. Feature Extraction
Converted textual data into numerical vectors using TF-IDF Vectorization.

## 6. Model Training
Trained multiple machine learning models for fake news classification.

## 7. Model Evaluation
Evaluated models using:
- Accuracy Score
- Classification Report
- Confusion Matrix

## 8. Prediction
Tested the trained model with custom news samples for prediction.

---

# Data Visualization Outputs

The project generates:
- Confusion Matrix
- Accuracy Comparison Graph

---

# Folder Structure

```text
fake-news-detection-nlp-project/
│
├── Fake_News_Detection.ipynb
├── Fake.csv
├── True.csv
├── README.md
└── requirements.txt
