
# 📊 Flipkart Reviews Sentiment Analysis using Python

This repository contains the **Sentiment Analysis Project** performed on Flipkart product reviews using Python and NLP techniques. The aim is to analyze customer feedback and classify sentiments as **Positive, Negative, or Neutral**. ([datascienceportfol.io][1])

---

## 📁 Project Overview

This project uses a dataset of product reviews from **Flipkart**, one of India’s largest e-commerce platforms. Using natural language processing techniques, we clean and preprocess text reviews, then perform sentiment analysis to understand customer opinions. ([datascienceportfol.io][1])

---

## 🛠️ Tools & Libraries

The project is implemented using:

* Python
* Pandas
* NLTK
* Matplotlib & Seaborn
* Plotly
* WordCloud
* VADER Sentiment Analyzer from NLTK

---

## 📥 Dataset

The dataset contains the following columns:

| Column Name  | Description                  |
| ------------ | ---------------------------- |
| Product_name | Name of product reviewed     |
| Review       | Customer review text         |
| Rating       | Review rating (1 to 5 stars) |

✔️ There are **no null values** in the dataset. ([datascienceportfol.io][1])

---

## 🧹 Data Preprocessing

Before analysis, the review text undergoes cleaning:

* Lowercasing
* Removal of punctuation and numbers
* Removal of stopwords
* Stemming using NLTK
* URLs, HTML tags & brackets removed

This helps improve the quality of text for sentiment analysis. ([datascienceportfol.io][1])

---

## 📊 Exploratory Data Analysis

### ⭐ Rating Distribution

The distribution of ratings is visualized using a pie chart, showing how users rated products.

### ☁️ Word Cloud

A word cloud visualizes the most frequently used words in the reviews, helping identify key topics mentioned by users.

---

## 📈 Sentiment Analysis

We use **VADER (Valence Aware Dictionary & sEntiment Reasoner)** to compute sentiment scores for each review:

* **Positive** score
* **Negative** score
* **Neutral** score

These are stored as separate columns in the dataset. ([datascienceportfol.io][1])

### 📌 Overall Sentiment Summary

```python
Positive:  923.55  
Negative:  96.77  
Neutral:  1283.69
```

📌 **Conclusion:** Most reviews are **Neutral**, followed by **Positive**, indicating general customer satisfaction with products/services. ([datascienceportfol.io][1])

---

## 🚀 How to Run

1. **Clone Repository**

```bash
git clone https://github.com/abinaya-345/Flipkart_reviews_sentiment_analysis_using_python.git
```

2. **Install Dependencies**

```bash
pip install pandas nltk matplotlib seaborn plotly wordcloud
```

3. **Download NLTK Resources**

```python
import nltk
nltk.download('stopwords')
nltk.download('vader_lexicon')
```

4. **Run Notebook / Script**

Open and execute the `Flipkart_reviews_sentiment_analysis_using_python.ipynb` notebook in Jupyter Notebook or Google Colab.

---

## 📌 Key Insights

* Majority of users give **high ratings** and **neutral-positive** sentiment.
* Neutral scores occur due to short or vague text that VADER interprets without strong polarity. ([datascienceportfol.io][1])

---

## 📈 Future Enhancements

You could further improve this project by:

✔️ Using machine learning models like **Logistic Regression, SVM, or LSTM**
✔️ Adding **GUI interface or Streamlit dashboard**
✔️ Deploying the model as a **Flask web app**
✔️ Comparing Flipkart sentiment with Amazon reviews

---

## 📌 Credits

This project was developed by **N. Abinaya** – Data Science Enthusiast.
Feel free to ⭐ the repo if you find it useful!
