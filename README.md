# Zomato Customer Sentiment Analysis

## Project Overview
This project analyses Zomato restaurant metadata and customer reviews using Exploratory Data Analysis (EDA), Natural Language Processing (NLP), and Machine Learning.

The primary objective is to classify customer reviews into three sentiment categories:
- Positive
- Negative
- Neutral

The project also explores restaurant pricing, cuisines, customer ratings, and review patterns to generate useful business insights.

## Dataset
The project uses two datasets:
- Zomato Restaurant Names and Metadata
- Zomato Restaurant Reviews

The cleaned NLP dataset contains 9,939 usable customer reviews.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- NLTK
- TextBlob
- Scikit-learn
- TF-IDF
- Truncated SVD
- Joblib
- Google Colab

## Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis with 15 visualizations
4. Hypothesis testing
5. Feature engineering
6. NLP text preprocessing
7. TF-IDF vectorization and dimensionality reduction
8. Sentiment classification using machine learning
9. Hyperparameter tuning and model evaluation
10. Model explainability and saving the trained pipeline

## Machine Learning Models
Three classification algorithms were implemented:
- Logistic Regression
- Linear Support Vector Classifier (LinearSVC)
- Random Forest Classifier

The tuned LinearSVC model was selected from the tuned model candidates.

### Final Model Results
- Accuracy: 89.03%
- Weighted Precision: 89.39%
- Weighted Recall: 89.03%
- Weighted F1-score: 89.12%
- Macro F1-score: 81.49%

## Model Deployment Preparation
The TF-IDF vectorizer, SVD transformer, and trained model were saved together using Joblib.

The saved pipeline was reloaded and tested on a new customer review, which was successfully classified as Positive.

## Business Applications
- Monitor customer sentiment
- Identify negative customer feedback
- Understand common customer concerns
- Support restaurant service improvements
- Generate data-driven customer experience insights

## Future Scope
- Implement restaurant clustering using K-Means
- Evaluate clusters using the Elbow Method and Silhouette Score
- Improve sentiment classification using more advanced NLP models
- Develop an interactive web application for real-time sentiment prediction

## Author
Harshita Mishra
