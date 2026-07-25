# SENTIMENT-ANALYSIS-USING-MACHINE-LEARNING-LSTM

A Sentiment Analysis project that classifies tweets into Positive, Negative, and Neutral sentiments using Machine Learning and Deep Learning techniques.

## About

This project analyzes tweets and predicts their sentiment using Natural Language Processing (NLP). It includes text preprocessing, feature extraction, machine learning models, and an LSTM neural network.

## Features

- Tweet preprocessing
- Stopword removal
- Lemmatization
- TF-IDF Vectorization
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- LSTM Deep Learning Model
- Classification Report
- Confusion Matrix

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
- Jupyter Notebook

## Dataset

Twitter US Airline Sentiment Dataset

File used:

```
Tweets.csv
```

## Project Structure

```
Sentiment-Analysis/
│
├── Tweets.csv
├── sentiment_analysis.ipynb
└── README.md
```

## How to Run

1. Clone the repository

2. Install required libraries

```bash
pip install pandas numpy nltk scikit-learn tensorflow matplotlib
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run

```
sentiment_analysis.ipynb
```

## Model Performance

| Metric | Value |
|----------|--------|
| Accuracy | 79% |
| Classes | Positive, Negative, Neutral |

## Output

The model predicts whether a tweet is:

- 😊 Positive
- 😐 Neutral
- 😞 Negative

Example:

```
Input:
"The service was amazing!"

Prediction:
Positive
```

## Future Improvements

- Bi-LSTM Model
- BERT Transformer Model
- Real-time Twitter Sentiment Analysis
- Streamlit Dashboard

## Author

**Simaal T. Kazi**
