

# 📄 Resume Screening App

This project is a **Resume Category Prediction App** built with **Streamlit**.  
It allows users to upload resumes (PDF, DOCX, or TXT) and automatically predicts the **job category** of the resume using a pre-trained machine learning model.

## 🚀 Features
- Upload resumes in **PDF, DOCX, or TXT** formats.
- Extracts text from resumes and cleans it.
- Uses **TF-IDF** for text vectorization.
- Classifies resumes into categories using a **Support Vector Classifier (SVC)**.
- Simple and interactive UI powered by **Streamlit**.


## 🗂️ Project Structure

ResumeScreeningApp/
├── app.py # Main Streamlit app
├── clf.pkl # Trained ML model (SVC)
├── tfidf.pkl # TF-IDF vectorizer
├── encoder.pkl # Label encoder for categories
├── Resume_Screening with Python.ipynb # Training notebook
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## 📊 Example Usage

1. Open the app in your browser after running it.
2. Upload a resume in PDF, DOCX, or TXT format.
3. The app extracts text, cleans it, and predicts the job category.
4. You will see the predicted category on the screen.


## 📦 Requirements

- Python 3.8+
- Streamlit
- scikit-learn
- PyPDF2
- python-docx

