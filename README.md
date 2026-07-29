# Arabic Sentiment Analysis AI

A Natural Language Processing (NLP) project that analyzes Arabic customer reviews and predicts their sentiment using Machine Learning.

This project includes Arabic text preprocessing, feature extraction, model comparison, and a Streamlit web application for real-time sentiment prediction.

---

## Project Objective

The objective of this project is to build an AI system capable of classifying Arabic reviews into:

- Positive sentiment
- Negative sentiment

The model learns from a large Arabic reviews dataset and predicts the sentiment of new user inputs.

---

## Dataset

Dataset used:

**330K Arabic Sentiment Reviews Dataset**

Dataset information:

- Number of reviews: 330,000
- Language: Arabic
- Type: Customer reviews

Main features:

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

### Data Preparation

The dataset was prepared through the following steps:

- Loading and exploring the dataset
- Checking missing values
- Cleaning Arabic text
- Removing unnecessary characters
- Preparing text data for machine learning

### Text Processing

Arabic reviews were transformed into numerical features using:

**TF-IDF (Term Frequency-Inverse Document Frequency)**

This technique allows machine learning algorithms to process textual data.

### Model Training and Evaluation

Three machine learning models were trained and compared:

| Model | Accuracy |
|---|---|
| Logistic Regression | 88.03% |
| SVM | 87.87% |
| Naive Bayes | 84.31% |

---

## Best Model

The best performing model was:

**Logistic Regression**

Accuracy:

**88.03%**

The final model was saved and integrated into the Streamlit application.

---

## Streamlit Application

A web application was developed using Streamlit.

The application allows users to:

- Enter an Arabic review
- Predict sentiment
- Display the confidence score

Example:

Input:

```
الخدمة ممتازة جدا وانصح بها
```

Output:

```
Positive 😊
Confidence Score: XX%
```

---

## Application Screenshot

![Arabic Sentiment Analysis App](images/app_screenshot.png)

---

## Model Comparison

![Model Comparison](images/model_comparison.png)

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
    ├── app_screenshot.png
    └── model_comparison.png
```

---

## How to Run the Project

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Results

This project demonstrates a complete NLP Machine Learning pipeline:

- Arabic text preprocessing
- Text feature extraction using TF-IDF
- Machine learning model comparison
- Sentiment classification
- Model deployment using Streamlit

---

## Future Improvements

Possible improvements:

- Use Deep Learning models such as LSTM or Transformers
- Add multi-class sentiment classification
- Deploy the application online

---

## Author

**Allae Elbaze**

Master's Student in Artificial Intelligence  
Ibn Tofail University - Morocco
