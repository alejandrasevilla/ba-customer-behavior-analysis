# British Airways Customer Behavior Analysis

This project explores airline customer behavior using two complementary approaches:

---

## 1. Review Sentiment Analysis (Web + NLP)

A natural language processing pipeline was developed to scrape, clean, and analyze 1,000+ customer reviews from [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways).  

### Key steps:
- Web scraping with `BeautifulSoup` + `requests`
- Text preprocessing: normalization, lemmatization, stopword filtering
- Sentiment scoring via `TextBlob`
- Word clouds, n-gram frequency (bigrams/trigrams), and topic modeling (LDA)
- Sentiment distribution and key phrases by polarity

Files:
- `sentiment-analysis/review_sentiment_analysis.ipynb` – End-to-end NLP pipeline
- `sentiment-analysis/sentiment_analysis_summary.pptx` – Executive summary slide

---

## 2. Booking Completion Prediction (Structured ML)

A machine learning model was built to predict booking completion using structured behavioral, trip, and demographic data.

### Key steps:
- Data cleaning, feature engineering, one-hot encoding
- Handling class imbalance with stratification and `class_weight=balanced`
- Random Forest modeling and threshold tuning
- Permutation-based feature importance analysis

Files:
- `booking-prediction/holiday_booking_model.ipynb` – Full modeling notebook
- `booking-prediction/BA_Review_Predict_Bookings.pptx` – Presentation of findings

---

## Tech Stack

`Python` · `pandas` · `scikit-learn` · `TextBlob` · `pyLDAvis`  
`nltk` · `matplotlib` · `seaborn` · `Jupyter` · `BeautifulSoup` · `WordCloud`

---

## Data

- Raw review data scraped from [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways)
- Booking dataset: `customer_booking.csv` (not included due to source restrictions)
- See [`data/README.md`](./data/README.md) for notes on preprocessing

---

## Outcomes

This project illustrates how text and tabular data can jointly inform business strategies in the airline industry, such as:

- Detecting service pain points and satisfaction drivers from customer language
- Predicting likelihood of booking completion based on behavior and context
- Informing marketing, UX, and product decisions through data storytelling

---

## About Me

[LinkedIn – Alejandra Sevilla](https://www.linkedin.com/in/alejandra-sevilla-m)  
Applied Data Scientist · M.S. in Analytics (Georgia Tech) · Bilingual (EN/ES)

---
