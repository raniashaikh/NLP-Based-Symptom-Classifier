# NLP-Based-Symptom-Classifier
End-to-end NLP pipeline for medical symptom classification using text preprocessing, TF-IDF feature extraction, and Linear SVM.


## Overview
This project focuses on classifying medical symptom descriptions using Natural Language Processing (NLP) and Machine Learning techniques. The goal is to take raw text input and predict the most relevant symptom category.

The project follows a complete NLP pipeline — from preprocessing raw text to building and evaluating classification models.

---

## What This Project Does
- Processes and cleans raw textual data
- Extracts meaningful features using TF-IDF
- Trains a classification model to predict symptom categories
- Evaluates model performance using standard metrics
- Visualizes patterns in the data using EDA techniques

---

## Techniques Used

### Text Processing
- Lowercasing and punctuation removal  
- Tokenization and stopword removal  
- Lemmatization for better word representation  
- Handling contractions and special characters  

### Feature Engineering
- TF-IDF vectorization  
- Uni-grams and bi-grams for context  

### Modeling
- Linear Support Vector Machine (SVM)  
- Multiple model configurations tested  

### Evaluation
- Accuracy, Precision, Recall, F1-score  
- Confusion matrix analysis  
- Validation performance comparison  

---

## Tools & Libraries
- Python  
- Pandas & NumPy  
- NLTK  
- SpaCy  
- Scikit-learn  
- Matplotlib  

---

## How the Project Works
1. Raw text data is cleaned and preprocessed  
2. Text is converted into numerical features using TF-IDF  
3. A classification model is trained on the processed data  
4. Model predictions are evaluated using validation data  
5. Final predictions are generated on unseen test data  

---

## Project Link
https://colab.research.google.com/drive/1OQvLUclPYJuYbqKfHJtWUXVda7PjbsP0?usp=sharing

---

## What I Learned
- Building an end-to-end NLP pipeline  
- Working with real-world text data  
- Understanding feature extraction techniques  
- Evaluating classification models properly  
- Improving model performance through experimentation  

---

## Future Improvements
- Try advanced models like BERT or deep learning approaches  
- Improve feature engineering strategies  
- Deploy the model as a web application  
- Expand the dataset for better accuracy  

---
