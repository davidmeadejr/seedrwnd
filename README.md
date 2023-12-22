# 🍀 Seedrwnd

<p align="center"><em>Planting ideas, growing possibilities.</em></p>

## Project Overview

This project involves analysing a dataset of around 50,000 tweets containing phrases like "startup idea," "start-up idea," or "business idea." The goal is to use machine learning and NLP to:

1. Identify tweets that specifically suggest a startup or business idea.
2. Categorise these tweets by industry.

## Checklist

### Data Preprocessing and Labeling

- [ ] Clean the tweets (remove URLs, mentions, hashtags, and non-textual content).
- [ ] Normalise the text (lowercasing, removing punctuation).
- [ ] Manually annotate a subset of tweets for binary classification (Idea/Not Idea).

### Feature Extraction and Model Training for Idea Identification

- [ ] Convert text data into numerical format (TF-IDF, Word2Vec, BERT embeddings).
- [ ] Choose and train a suitable machine learning model (Logistic Regression, Naive Bayes, etc.).
- [ ] Evaluate the model (accuracy, precision, recall, F1-score).
- [ ] Tune the model for better performance.

### Industry Categorisation

#### Supervised Learning Approach

- [ ] Manually categorise another subset of tweets into different industries (if labels are available).
- [ ] Train a multi-class classification model (SVM, Random Forest, neural networks).
- [ ] Evaluate the model using appropriate metrics.

### Tools and Libraries

- [ ] Use Pandas for data manipulation.
- [ ] Apply NLTK/SpaCy for NLP-related tasks.
- [ ] Utilise Scikit-learn for machine learning models.
- [ ] Implement Matplotlib/Seaborn for data visualization.

### Advanced NLP Models

- [ ] (Optional) Explore transformer models like BERT for improved feature extraction and classification.

### Final Steps

- [ ] Refine models based on initial results (if neccessary).
- [ ] A dedicated page or post to showcase the tweets.
- [ ] A blog post about this project and what I learned.

---
