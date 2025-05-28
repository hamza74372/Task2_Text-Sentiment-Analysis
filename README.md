# Task 2: Text Sentiment Analysis

## Description
This task involves building a sentiment analysis model using the IMDB Reviews dataset. The goal is to classify movie reviews as either positive or negative.

## Steps Followed

1. **Dataset**  
   - Used the IMDB dataset from `tensorflow_datasets`.
   - Converted the dataset to pandas DataFrames for easier manipulation.

2. **Text Preprocessing**  
   - Lowercased text  
   - Removed punctuation and stopwords  
   - Applied lemmatization using NLTK

3. **Feature Engineering**  
   - Converted text to numerical features using TF-IDF (max 5000 features)

4. **Model Training**  
   - Trained a Logistic Regression classifier to predict sentiments

5. **Evaluation**  
   - Evaluated the model using accuracy and classification report

6. **Prediction Function**  
   - Added a simple function to test sentiment prediction on new text inputs

## Results
- The model achieved high accuracy and good precision/recall on both positive and negative reviews.

## How to Run
1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. Use the `predict_sentiment()` function to test custom reviews

---

