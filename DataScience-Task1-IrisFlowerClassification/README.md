 Data Science Internship - Task 1: Iris Flower Classification
       This folder contains the submission for Task 1 of my Data Science Internship at Oasis Infobyte.
 📋 Project Overview
       The goal of this project is to build a machine learning model capable of classifying Iris flowers into three distinct species (Setosa, Versicolor, and Virginica) based on their physical measurements: sepal length, sepal width, petal length, and petal width.

 ⚙️ Tech Stack & Tools
           Language: Python
           Libraries: Pandas, NumPy, Scikit-learn
           Visualization: Matplotlib, Seaborn
           Environment: Jupyter Notebook (Google Colab)

 🚀 Implementation Steps
        1. Data Loading : Loaded the built-in Iris dataset directly from `sklearn.datasets.load_iris()`.
        2. Exploratory Data Analysis (EDA) : Checked data shapes, data types, null values, and computed descriptive statistics.
        3. Data Visualization : Generated pair plots and box plots to analyze feature distributions and separations by species.
        4. Feature Selection & Split : Prepared target variables and split the dataset using an 80/20 train-test ratio.
        5. Model Training : Implemented and evaluated two classifiers:
                 1.Logistic Regression
                 2.Decision Tree Classifier
        6. Evaluation : Evaluated model performances using Accuracy Scores, Confusion Matrices, and Classification Reports (Precision, Recall, F1-Score).

 📊 Key Results
        Both Logistic Regression and Decision Tree models successfully achieved an **100% accuracy score** on the testing dataset due to the clean and linearly separable nature of the features.
