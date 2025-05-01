#  Naive Bayes and Text Mining

# Text Classification and Sentiment Analysis of Blogs

This project focuses on classifying blog posts into different categories and performing sentiment analysis on the text data. It utilizes Natural Language Processing (NLP) techniques and machine learning models to achieve these tasks.

## Project Overview

The project involves the following key steps:

1. **Data Exploration and Preprocessing:**
   - Load and explore the dataset of blog posts.
   - Preprocess the text data by removing special characters, converting to lowercase, tokenizing, removing stop words, and applying stemming.
   - Extract features using TF-IDF vectorization.

2. **Naive Bayes Model for Text Classification:**
   - Split the data into training and testing sets.
   - Train a Multinomial Naive Bayes model on the training data.
   - Evaluate the model's performance on the testing data using metrics like accuracy, precision, recall, and F1-score.

3. **Sentiment Analysis:**
   - Utilize TextBlob to perform sentiment analysis on both the original and preprocessed text data.
   - Analyze the distribution of sentiments (positive, negative, neutral) across different categories.
   - Visualize the sentiment distribution using bar charts and heatmaps.

4. **Evaluation and Discussion:**
   - Discuss the model's performance and analyze its strengths and weaknesses.
   - Interpret the sentiment analysis results and draw insights into the emotional tone of the blog posts within each category.

## Requirements

- Python 3.x
- Libraries: pandas, scikit-learn, nltk, spacy, wordcloud, textblob

## Usage

1. Install the required libraries:
