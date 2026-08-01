# Task 4 - Email Spam Detection with Machine Learning

## 📌 Objective
The objective of this project is to build a Machine Learning model that classifies emails/messages as **Spam** or **Ham (Legitimate)** using Natural Language Processing (NLP) techniques.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Regular Expressions (re)

## 📂 Dataset
- SMS Spam Collection Dataset
- Contains two classes:
  - Ham (Legitimate messages)
  - Spam (Unwanted messages)

## 🔄 Project Workflow
1. Import required libraries.
2. Load the dataset.
3. Explore the dataset and check class distribution.
4. Preprocess text (lowercase conversion, punctuation removal, stopword removal).
5. Convert text into numerical features using TF-IDF Vectorizer.
6. Split the dataset into training and testing sets.
7. Train two machine learning models:
   - Multinomial Naive Bayes
   - Logistic Regression
8. Evaluate the models using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
9. Compare the performance of both models.

## 📊 Results
- Both models successfully classified spam and ham messages.
- Multinomial Naive Bayes achieved around **97% accuracy**.
- Logistic Regression achieved around **95% accuracy**.
- Naive Bayes performed slightly better on this dataset.

## ✅ Conclusion
This project demonstrates how NLP and Machine Learning can effectively detect spam messages. After preprocessing the text and applying TF-IDF vectorization, both models produced high accuracy. The results show that Machine Learning can automatically identify spam messages and help improve email filtering systems.
