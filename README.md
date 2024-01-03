# 🍀 Seedrwnd

<p align="center"><em>You will get rich by giving society what it wants but does not yet know how to get at scale.</em></p>
<p align="center"><em>- Naval Ravikant</em></p>

## Project Overview

This project involves analysing a dataset of around 50,000 posts on X containing phrases like "startup idea," "start-up idea," or "business idea." The goal is to use machine learning techniques to:

1. Discover and Highlight: Extract posts where users have articulated startup or business ideas they envision.
2. Categorize with Precision: Methodically classify these ideas into distinct industry sectors using NLP algorithms.
3. Showcase Innovatively: Feature these organized ideas on a specialized page, turning data into a source of inspiration and opportunity discovery.

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
- [ ] Implement Matplotlib/Seaborn for data visualisation.

### Final Steps

- [ ] Refine models based on initial results (if neccessary).
- [ ] A dedicated page or post to showcase the tweets.
- [ ] A blog post about this project and what I learned.

---
