📊 Sentiment & Topic Analysis of Customer Reviews
This repository contains a complete pipeline for text analysis on customer reviews, including preprocessing, sentiment analysis, and visualization. 
It transforms raw review data into actionable insights using Python, NLTK, TextBlob, and various visualization tools.

🚀 Features
✅ Data Preprocessing

Remove missing values

Lowercasing, cleaning special characters

Tokenization & stopword removal

✅ Sentiment Analysis

Uses TextBlob for polarity scoring

Categorizes reviews as Positive, Negative, Neutral

✅ Topic Modeling

Extracts latent topics

Generates word clouds for each topic

✅ Visualizations

Sentiment distribution pie chart

Word clouds for each topic

🛠️ Tech Stack
Python

pandas

openpyxl

nltk

textblob

matplotlib

seaborn

wordcloud

📂 Workflow
Load Data → Import customer review data from gba_2.xlsx.

Preprocess Text → Clean, tokenize, and remove stopwords. The flipkart gba_1.ipynb notebook handles these steps.

Save Preprocessed Data → The cleaned data is saved to processed_reviews.xlsx.

Sentiment Analysis → Sentiment scores and categories are generated and saved to reviews_with_sentiment.xlsx.

Topic Modeling → Word clouds are generated to highlight key topics.

Visualizations → Pie charts and word clouds are created to visualize the findings.

▶️ How to Run
Make sure you have the required libraries installed by running the following commands in your terminal or a Jupyter notebook cell:

Bash

pip install pandas openpyxl
pip install nltk
pip install textblob
pip install matplotlib seaborn wordcloud
First, run the flipkart gba_1.ipynb notebook to preprocess the data and create the preprocessed_data.xlsx file.

Next, run the gba_2.ipynb notebook to perform the sentiment and topic analysis, and generate the visualizations.
