# Question-Paper-Difficulty-Analysis
NLP project that uses OCR to extract text from college exam question paper images and classifies questions into Easy/Medium/Hard with difficulty scoring and visualization.

# Question Paper Difficulty Analysis (OCR + NLP)

This project analyzes **college exam question papers (images)** and automatically classifies questions into:
✅ **Easy**  
✅ **Medium**  
✅ **Hard**

It uses **OCR (Tesseract)** to extract text from question paper images, applies **NLP preprocessing**, and then predicts difficulty using a **Machine Learning model**.

---

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
