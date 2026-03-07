# Resume-Classification-System
Machine Learning project that classifies resumes into job categories using NLP, TF-IDF and SVM with a Streamlit deployment.


This project is a Machine Learning application that automatically classifies resumes into job categories using Natural Language Processing (NLP) techniques.

The system processes resume text, extracts features using TF-IDF, and predicts the most relevant job role using a Support Vector Machine (SVM) classifier.

A Streamlit web application is built to allow users to upload or paste resume text and receive predictions with confidence scores.

## Project Workflow

Resume Input  
→ Text Preprocessing  
→ TF-IDF Feature Extraction  
→ SVM Model  
→ Predicted Job Category  

## Technologies Used

Python  
Scikit-Learn  
NLP (NLTK)  
TF-IDF Vectorization  
Support Vector Machine (SVM)  
Streamlit (Deployment)  
Matplotlib & Pandas  

## Features

- Resume text preprocessing
- Feature extraction using TF-IDF
- Multiple model comparison (Logistic Regression, SVM, Naive Bayes)
- Model evaluation using accuracy, confusion matrix and cross validation
- Streamlit web interface for predictions
- Confidence score and probability visualization

## Model Performance

| Model | Accuracy |
|------|--------|
| Logistic Regression | 81% |
| SVM | 87% |
| Naive Bayes | 87% |

SVM was selected as the final model due to stable performance and better handling of high-dimensional TF-IDF features.


## Deployment

The trained model is deployed using Streamlit.

Users can:
• Upload resumes  
• Paste resume text  
• Receive predicted job category  
• View prediction confidence  


## Example Output

Input Resume Skills:
Python, SQL, Machine Learning

Output:
Predicted Category: Data Science  
Confidence Score: 92%


## Installation

Clone the repository:
