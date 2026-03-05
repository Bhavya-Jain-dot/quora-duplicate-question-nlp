Quora Duplicate Question Detection (NLP Project)
This project detects whether two questions asked on Quora are duplicates or not using Natural Language Processing and Machine Learning techniques.

The system analyzes semantic similarity between two questions and predicts whether they represent the same intent.

Problem Statement
Quora contains millions of user-generated questions. Many users ask the same question in different ways, creating duplicate content.

Example:

Question 1: What is Artificial Intelligence?
Question 2: Explain AI.

Both questions have the same meaning.

The goal of this project is to automatically detect duplicate question pairs.

Project Pipeline
Data Cleaning
Text Preprocessing
Feature Engineering
Feature Extraction (TF-IDF / similarity features)
Model Training
Model Evaluation
Streamlit Web Application
Features Used
The model uses several NLP-based features:

Bag of Words
TF-IDF vectors
Token based features
Word overlap features
Length based features
Fuzzy string matching
Cosine similarity
Machine Learning Models
The following models were tested:

Logistic Regression
Random Forest
XGBoost
The best performing model was selected for the final application.

Web Application
A Streamlit web application allows users to input two questions and check if they are duplicates.

Example:

Input: Question 1: What is Machine Learning?
Question 2: Explain Machine Learning.

Output: Duplicate Question

Installation
Clone the repository:

git clone https://github.com/your-username/quora-duplicate-question-nlp.git

Move to project folder:

cd quora-duplicate-question-nlp

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

Technologies Used
Python
Pandas
NumPy
Scikit-learn
NLTK
Streamlit
Matplotlib
Seaborn
Dataset
Quora Question Pairs dataset:

https://www.kaggle.com/c/quora-question-pairs

Author
Bhavya
