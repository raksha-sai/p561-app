# p561-app
## 🧠 P-561 Resume Classification using Time Series NLP
This project is an AI-powered resume classification system built as part of the P-561 team project. It leverages natural language processing and machine learning to classify resumes into one of several predefined job categories and extract relevant candidate information. The final model is deployed using Streamlit for interactive use.
## 📌 Project Objective
To build a smart resume classification tool that can:

* Automatically categorize resumes using NLP and ML techniques.
* Extract candidate details (name, email, skills, experience, etc.)
* Display structured resume summaries and visual insights.
* Allow resume uploads and provide predictions with downloadable results.
## 🔧 Tech Stack
* Python 3
* NLP: TF-IDF Vectorizer
* ML Models: Logistic Regression (Best model with 100% accuracy)
* Libraries: Streamlit, scikit-learn, pandas, matplotlib, docx2txt, openpyxl
* Deployment: Streamlit Cloud + GitHub
## 📂 Dataset Structure
'''text
P-561 Dataset/
├── React Developer/
│   ├── resume1.docx
│   └── ...
├── SQL Developer/
├── Workday/
└── PeopleSoft/
'''
Each folder contains '.docx' resumes belonging to the respective job category.
