# Arabic Sentiment Analysis AI

A Natural Language Processing (NLP) project that analyzes Arabic customer reviews and predicts their sentiment using Machine Learning.

This project covers the complete machine learning workflow, from data preparation and text processing to model training and deployment with a Streamlit application.

---

## Project Overview

The goal of this project is to build an AI system capable of classifying Arabic reviews into two categories:

- Positive sentiment
- Negative sentiment

The trained model can analyze new Arabic texts and predict the corresponding sentiment.

---

## Dataset

Dataset used:

**Arabic Sentiment Reviews Dataset**

Dataset information:

- Number of reviews: 330,000
- Language: Arabic
- Type: Customer reviews
- Task: Binary sentiment classification

Main columns:

- `content` : Arabic review text
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

The dataset was prepared through:

- Data loading and exploration
- Missing values analysis
- Arabic text cleaning
- Text preprocessing
- Dataset preparation for machine learning

---

### 2. Text Feature Extraction

The Arabic reviews were transformed into numerical features using:

**TF-IDF (Term Frequency-Inverse Document Frequency)**

This method converts text data into a format that machine learning algorithms can process.

---

### 3. Model Training and Evaluation

Different machine learning algorithms were trained and compared:

| Model | Accuracy |
|---|---|
| Logistic Regression | 88.03% |
| SVM | 87.87% |
| Naive Bayes | 84.31% |

---

## Best Model

The best performance was achieved by:

**Logistic Regression**

Accuracy:

**88.03%**

The final model was integrated into the Streamlit application for real-time prediction.

---

## Streamlit Application

A web application was developed using Streamlit.

The application allows users to:

- Enter an Arabic review
- Predict the sentiment
- Display the prediction result

Example:

Input:

```
الخدمة ممتازة جدا وانصح بها
```

Output:

```
Positive
```

---

## Application Screenshot

![Streamlit Application](images/app_screenshot.png)

---

## Project Structure

```
Arabic-Sentiment-Analysis/

│
├── README.md
├── app.py
├── requirements.txt
├── sentiment_analysis.ipynb
│
├── data/
│   └── arabic_sentiment_reviews.csv
│
├── models/
│   ├── sentiment_model.pkl
│   └── tfidf_vectorizer.pkl
│
└── images/
    └── app_screenshot.png
```

---

## How to Run the Project

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## Results

This project demonstrates a complete NLP machine learning pipeline:

- Arabic text preprocessing
- Feature extraction using TF-IDF
- Machine learning model comparison
- Sentiment classification
- Deployment with Streamlit

---

## Future Improvements

Possible improvements:

- Use Deep Learning models such as LSTM or Transformers
- Support more sentiment categories
- Deploy the application online

---

## Author

**Allae Elbaze**

Master's Student in Artificial Intelligence  
Ibn Tofail University - Morocco
