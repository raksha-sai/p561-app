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
## 📁 Dataset Structure

```text
P-561 Dataset/
├── React Developer/
│   ├── resume1.docx
│   └── ...
├── SQL Developer/
├── Workday/
└── PeopleSoft/
```

Each folder contains `.docx` resumes belonging to the respective job category.
## ⚙️ How it Works
1. Resumes are preprocessed using TF-IDF vectorization.
2. A logistic regression model is trained to classify resumes into 4 categories.
3. Information like name, location, email, phone, company, skills, experience, and salary are extracted using regex.
4. The Streamlit app allows you to:
   <ul type="circle">
     <li>Upload and predict resumes.</li>
     <li>View extracted data in tables.</li>
     <li>Browse by category.</li>
     <li>See visualizations (bar, pie chart).</li>
     <li>Download predictions as Excel.</li>
   </ul>
## 🚀 Deployment Guide

```text
git clone https://github.com/your-username/p561-resume-classifier.git
cd p561-resume-classifier
```
## 📦 Install Requirements
```text
pip install -r requirements.txt
```
## ▶️ Run Streamlit App
```text
streamlit run app.py
```
## 🌐 Streamlit Cloud Deployment
1. Push your project to GitHub.
2. Visit Streamlit Cloud.
3. Connect your GitHub and select the repo.
4. Set `app.py` as the main file.
5. Click Deploy.
   
## 🧪 Sample Resume Format
```text
Name: Priya Sharma
Location: Bangalore
Email: priyasharma.dev@gmail.com
Phone: +91 9876543210
Company: Infosys
Skills: React, JavaScript, HTML, CSS, Redux, REST API, Git
Experience: 3 years
Salary: ₹6,50,000
```
## 📈 Features Summary
* ✅ Resume upload & prediction
* 📤 Download results as Excel
* 📊 Resume dashboard (category-wise)
* 📋 Resume summary + details extraction
* 🎯 Logistic Regression model with 100% accuracy

## 🧠 Future Enhancements
* Add PDF resume support
* Add more job categories (e.g., Data Analyst, Backend Developer)
* Use advanced NLP techniques like BERT or LLMs
* Enable bulk resume processing
## 🙋‍♀️ Team & Credits
Built by D R Raksha Sai Gowda, Kalpana M, Soujanya C ,Samuel U for the DATA SCIENCE Course Project.
