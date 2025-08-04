# 🧠 PRODIGY_DS_04 – Task 04: Social Media Sentiment Analysis

## 📌 Task Description

**Objective:**  
Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

This task focuses on preprocessing social media text, exploring sentiment distribution, and training a machine learning model to classify sentiments as **Positive**, **Negative**, **Neutral**, or **Irrelevant**.

---

## 📁 Dataset Used

- **Source:** Provided social media sentiment dataset  
- **Total Records:** 15,000  
- **Features:**
  - `Text`: User-generated content (social media post)
  - `Sentiment`: Target label with classes – *Positive, Negative, Neutral, Irrelevant*

---

## 🧹 Data Preprocessing Steps

✅ Removed special characters, links, and mentions  
✅ Converted all text to lowercase  
✅ Removed stopwords and applied tokenization  
✅ Vectorized the text using **TF-IDF**  

---

## 📊 Exploratory Data Analysis (EDA)

Conducted to understand the sentiment distribution and text length:

- **Sentiment Distribution Countplot**
- **Word Cloud per Sentiment**
- **Text Length vs Sentiment**
- **Most Common Words in Each Category**

---

## 🤖 Model Building

- **Algorithm Used:** Logistic Regression  
- **Text Representation:** TF-IDF vectorizer  
- **Train-Test Split:** 80/20  
- **Accuracy Achieved:** `83%`  

---

## 🛠️ Libraries Used

- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib`, `seaborn` – Visualization  
- `nltk`, `re` – Text preprocessing  
- `scikit-learn` – ML modeling and evaluation  

---

## 📷 Visual Outputs

- 📊 Sentiment Class Distribution (Bar Plot)  
- ☁️ Word Clouds for each Sentiment  
- 📈 Text Length Distribution by Sentiment  

---

## ✅ Outcome

- Built an end-to-end pipeline for sentiment classification  
- Achieved high classification accuracy using Logistic Regression  
- Extracted meaningful insights from social media opinions  
- Prepared a clean, labeled dataset ready for further NLP tasks

---

> 💡 *This analysis can help brands and organizations monitor public perception and detect early signals of satisfaction or dissatisfaction through social media.*
