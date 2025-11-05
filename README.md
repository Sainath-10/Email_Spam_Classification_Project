# Email_Spam_Classification_Project
Email Spam Classification Using Multinomial Naive Bayes & Natural Language ToolKit

# 📧 Email Spam Classification using MultinomialNB

A Machine Learning project that uses **Natural Language Processing (NLP)** for text cleaning and applies the **Multinomial Naive Bayes** algorithm to classify emails as Spam or Not Spam.

---

## 📘 Overview

This project demonstrates how to use **text preprocessing** + **statistical ML models** for spam detection.
It involves:

* Cleaning and preprocessing email text
* Converting text into numerical features using Bag-of-Words
* Training a MultinomialNB classifier
* Evaluating model performance using accuracy and confusion matrix

The model learns patterns from words that commonly appear in spam messages and predicts whether a new email is spam or genuine.

---

## 📂 Dataset Description

* **Input**: Text messages (emails)
* **Classes**: Spam / Ham (Not Spam)
* **Goal**: Identify unwanted/spam mail

Dataset is transformed into lowercase, cleaned, stopwords removed, and stemmed for better feature extraction.

---

## ⚙️ Tech Stack

* **Language**: Python
* **Libraries**: Pandas, NumPy, NLTK, Scikit-learn, Seaborn, Matplotlib

---

## 🧩 Project Workflow

### 1. Importing Libraries
Essential Python modules for data processing, NLP, and modeling.

### 2. Data Preprocessing
* Removing punctuation & symbols
* Converting to lowercase
* Removing stopwords (NLTK)
* Stemming (Snowball Stemmer)

### 3. Feature Extraction
Text converted to numerical form using:
* CountVectorizer (Bag-of-Words)

### 4. Model Building
Classifier used:  
**Multinomial Naive Bayes (MultinomialNB)**

### 5. Evaluation
Performance checked using:
* Accuracy Score
* Confusion Matrix

---

## 📊 Results

**Accuracy : 98.38**

---
