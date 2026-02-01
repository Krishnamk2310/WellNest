# 🏥 WellNest – AI-Powered Disease Prediction System

WellNest is an AI-based healthcare application that predicts possible diseases based on user symptoms and provides personalized health recommendations. The system uses machine learning models trained on a Kaggle clinical dataset and delivers real-time predictions via a Flask REST API.

---

## 🚀 Features

- 🔍 Predicts **46 diseases** based on user-provided symptoms  
- 🧠 Machine learning–based disease classification  
- 🍽️ Personalized recommendations:
  - Diet plans  
  - Medicines  
  - Workout suggestions  
  - Preventive measures  
  - Foods to eat and avoid  
- ⚡ Real-time predictions through REST APIs  
- 📱 Responsive and user-friendly interface  

---

## 🛠️ Tech Stack

**Backend & ML**
- Python  
- TensorFlow  
- Scikit-learn  
- Flask (REST API)

**Frontend**
- Bootstrap  
- HTML  
- CSS  
- JavaScript  

**Dataset**
- Kaggle (symptom-to-disease clinical dataset)

---

## 🧠 Machine Learning Overview

- Trained and evaluated classification models using **TensorFlow** and **Scikit-learn**
- Symptom-based disease prediction pipeline
- Preprocessed structured clinical data
- Model inference exposed via Flask APIs

---

## 🔗 API Functionality

- Accepts symptoms as input
- Returns:
  - Predicted disease  
  - Diet recommendations  
  - Suggested medicines  
  - Workout plans  
  - Preventive measures  
  - Foods to eat and avoid  

---

## 📸 User Interface

- Responsive UI built with Bootstrap
- Displays disease predictions and personalized guidance
- Designed for clarity and ease of use

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/Krishnamk2310/WellNest.git
cd WellNest
pip install -r requirements.txt
python app.py
