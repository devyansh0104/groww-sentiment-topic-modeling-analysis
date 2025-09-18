# 📊 Sentiment & Topic Analysis of Customer Reviews

This repository contains a **complete pipeline for text analysis** on customer reviews, including preprocessing, sentiment analysis, topic modeling, and visualization. 
It transforms raw review data into actionable insights using **Python, NLTK, TextBlob, Scikit-learn, and visualization tools**.

---

## 🚀 Features

- ✅ **Data Preprocessing**  
  - Remove missing values  
  - Lowercasing, cleaning special characters  
  - Tokenization & stopword removal  

- ✅ **Sentiment Analysis**  
  - Uses **TextBlob** for polarity scoring  
  - Categorizes reviews as *Positive, Negative, Neutral*  

- ✅ **Topic Modeling**  
  - TF-IDF + **NMF (Non-negative Matrix Factorization)**  
  - Extracts top keywords for each topic  
  - Assigns dominant topics to reviews  

- ✅ **Visualizations**  
  - Sentiment distribution pie chart  
  - Top words per topic (bar plots)  
  - Word clouds for each topic  

---

## 🛠️ Tech Stack

- **Python**  
- `pandas`, `numpy`  
- `nltk`, `textblob`  
- `scikit-learn`  
- `matplotlib`, `seaborn`, `wordcloud`  

---

## 📂 Workflow

1. **Load Data** → Import Excel file (`gba_2.xlsx`)  
2. **Preprocess Text** → Clean, tokenize, and remove stopwords  
3. **Save Preprocessed Data** → `processed_reviews.xlsx`  
4. **Sentiment Analysis** → Save results in `reviews_with_sentiment.xlsx`  
5. **Topic Modeling** → Extract 5 latent topics using NMF  
6. **Visualizations** → Pie chart, bar plots, word clouds  

   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
