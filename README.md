# 🎬 NextFlix: Netflix Content Analysis & Recommendation App

![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-orange?style=flat-square&logo=streamlit)
![Python](https://img.shields.io/badge/Python-3.9+-blue.svg?style=flat-square&logo=python)
![License](https://img.shields.io/badge/License-Educational-lightgrey?style=flat-square)
![Status](https://img.shields.io/badge/Project-Academic%20Capstone-success?style=flat-square)

> A machine learning-powered app that predicts missing metadata, estimates IMDb and Rotten Tomatoes scores, and classifies Netflix content recommendations using integrated datasets.

---

## 🚀 Live App

🎯 [**Try the Live App →** https://nextflix.streamlit.app/](https://nextflix.streamlit.app/)  
📎 Hosted on Streamlit Cloud

---

## 📌 Project Summary

This project addresses the issue of missing or inconsistent metadata in Netflix’s global library, which impacts discoverability and personalization. Using data from Netflix (2019), IMDb, and Rotten Tomatoes, we built predictive models to fill gaps and classify content recommendations for better decision-making.

---

### ✅ Features:
- **Genre Prediction** via TF-IDF + Logistic Regression (multi-label)
- **IMDb & RT Rating Estimation** via Ridge & Linear Regression
- **Binary Recommendation Classification** based on IMDb model (F1: 0.70, Recall: 0.73)
- **Interactive Web App** built with Streamlit for real-time user inputs and predictions

---

## 🖥️ App screenshot
![image](https://github.com/user-attachments/assets/547ff152-b2fa-4363-a817-8935102c5758)

---

🗂️ Project Structure
```plaintext
├── app.py                          # Streamlit web app
├── /code/Analysis Code.ipynb       # Model training & logic
├── /datasets                       # CSV/TSV input files (Netflix, IMDb, RT)
├── requirements.txt                # Dependency list
└── README.md                       # You're here!

---

## 🧪 How to Use Locally

```bash
git clone https://github.com/Sowfia28/Netflix-analysis.git
cd Netflix-analysis
pip install -r requirements.txt
streamlit run app.py
