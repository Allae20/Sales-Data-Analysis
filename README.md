# Arabic Sentiment Analysis AI

Machine Learning NLP project for Arabic sentiment classification.

The project analyzes Arabic customer reviews and predicts whether the sentiment is positive or negative.

## Objective

Build an AI system capable of understanding Arabic text and classifying customer opinions.

## Dataset

Dataset: 330K Arabic Sentiment Reviews Dataset

- 330,000 Arabic reviews
- Text classification problem
- Two classes:
  - Positive
  - Negative

## Technologies

- Python
- Pandas
- Scikit-learn
- NLP
- TF-IDF
- Machine Learning
- Streamlit

## Workflow

### Data Processing

- Data loading and exploration
- Missing values checking
- Arabic text cleaning
- Text preprocessing

### Feature Extraction

TF-IDF was used to transform Arabic text into numerical features.

### Models Tested

| Model | Accuracy |
|---|---|
| Logistic Regression | 88.03% |
| SVM | 87.87% |
| Naive Bayes | 84.31% |

## Best Model

Logistic Regression achieved the best performance:

Accuracy: 88.03%

## Streamlit Application

The application allows users to:

- Enter Arabic reviews
- Predict sentiment
- Display confidence score

## Screenshot

![Application Screenshot](images/app_screenshot.png)

## Project Structure

- app.py
- sentiment_analysis.ipynb
- requirements.txt
- data/
- models/
- images/

## Run Project

Install:

pip install -r requirements.txt

Run:

streamlit run app.py

## Author

Allae Elbaze

Master's Student in Artificial Intelligence  
Ibn Tofail University - Morocco
