# Question Paper Difficulty Analysis (OCR + NLP)

This project analyzes **college exam question papers (images)** and automatically classifies questions into:
✅ **Easy**  
✅ **Medium**  
✅ **Hard**

It uses **OCR (Tesseract)** to extract text from question paper images, applies **NLP preprocessing**, and then predicts difficulty using a **Machine Learning model**.

---
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ravuribhargav/Question-Paper-Difficulty-Analysis/blob/main/Question_Paper_Difficulty_Analysis.ipynb)


## 🚀 Features
- Extracts text from **question paper images** using OCR
- Cleans and preprocesses text
- Segments the paper into individual questions
- Classifies questions into **Easy / Medium / Hard**
- Calculates an overall **paper difficulty score**
- Generates visualizations and saves results

---

## 🧠 Approach / Pipeline
1. Input: Question paper images (.jpg / .png)
2. OCR Extraction (Tesseract + OpenCV preprocessing)
3. Text Cleaning + Normalization
4. Question Segmentation
5. Feature Extraction (TF-IDF + optional numeric features)
6. ML Model: Logistic Regression
7. Output: Difficulty labels + score + graphs

---

## 📂 Project Structure
