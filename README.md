# Duplicate-Question-Pair

## 🌟 Overview
This NLP project uses machine learning to determine if two questions are duplicates based on their textual content. The application is built using Streamlit for the frontend and machine learning models for detecting duplicate question pairs.

## ✨ Features
- Text Input: Users can input two questions into the interface.
- Duplicate Detection: The model predicts whether the two questions are duplicates or not.
- Preprocessing: The input questions undergo preprocessing (removing stop words, tokenization, handling special characters, etc.        
- Feature Engineering: Various features are calculated, including token-based features, length-based features, and fuzzy string matching features.

## 🛠️ Requirements
- Python 3.x
- Streamlit
- scikit-learn
- fuzzywuzzy
- Levenshtein
- BeautifulSoup
- pickle

## 🚀 How It Works
1. Text Preprocessing: The input questions undergo preprocessing where:
- Special characters are replaced with text equivalents.
- Contractions are expanded.
- HTML tags and punctuations are removed.
2. Feature Extraction: Several features (such as common words, token-level features, fuzzy matching scores, and length features) are extracted from the processed questions.
3. Prediction: The model uses the extracted features to predict whether the questions are duplicates or not.
4. Streamlit UI: The Streamlit interface allows users to input two questions and see the result (Duplicate/Not Duplicate).

Dataset Link :- https://www.kaggle.com/c/quora-question-pairs
