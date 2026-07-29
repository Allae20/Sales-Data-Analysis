# Arabic Sentiment Analysis AI

A Natural Language Processing (NLP) project that analyzes Arabic customer reviews and predicts their sentiment using Machine Learning.

The project includes text preprocessing, model comparison, and a Streamlit web application for real-time sentiment prediction.

---

## Project Overview

The objective of this project is to build an AI system capable of classifying Arabic reviews into:

- Positive sentiment
- Negative sentiment

The model learns from a large Arabic reviews dataset and can automatically analyze new user inputs.

---

## Dataset

Dataset:

**330K Arabic Sentiment Reviews Dataset**

Details:

- Number of reviews: 330,000
- Language: Arabic
- Type: Customer reviews

Main features:

- `content` : Review text
- `label` : Sentiment label

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Machine Learning
- Streamlit

---

## Project Workflow

### 1. Data Preparation

Steps performed:

- Dataset loading
- Data exploration
- Missing values checking
- Arabic text cleaning
- Text preprocessing

---

### 2. Text Feature Extraction

Arabic text was converted into numerical features using:

**TF-IDF Vectorization**

This technique allows machine learning algorithms to process textual data.

---

### 3. Model Training and Comparison

Three machine learning models were evaluated:

| Model | Accuracy |
|---|---|
| Logistic Regression | 88.03% |
| SVM | 87.87% |
| Naive Bayes | 84.31% |

---

## Best Model

The best results were achieved using:

**Logistic Regression**

Accuracy:

**88.03%**

The model was selected and integrated into the final application.

---

## Streamlit Application

A web application was developed using Streamlit.

The application allows users to:

- Enter an Arabic review
- Predict sentiment
- Display prediction confidence score

Example:

Input:
