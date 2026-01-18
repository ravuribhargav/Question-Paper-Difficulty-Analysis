# Question Paper Difficulty Analysis (OCR + NLP)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ravuribhargav/Question-Paper-Difficulty-Analysis/blob/main/Question_Paper_Difficulty_Analysis.ipynb)

This project analyzes **college exam question papers (image format)** and automatically classifies questions into:

✅ Easy  
✅ Medium  
✅ Hard  

It uses **OCR (Tesseract + OpenCV preprocessing)** to extract text, then applies **NLP + Machine Learning** to predict difficulty levels and calculate an overall paper difficulty score.

---

## 🚀 Features
- Extract text from question paper **images** using OCR
- Clean and preprocess the extracted text
- Segment the paper into individual questions
- Classify questions into **Easy / Medium / Hard**
- Compute overall **paper difficulty score**
- Visualize results and save outputs

---

## 🧠 Workflow / Pipeline
1. **Input**: Question paper images (`.jpg`, `.png`, `.jpeg`)
2. **OCR Extraction**: OpenCV preprocessing + Tesseract OCR
3. **Text Cleaning**
4. **Question Segmentation**
5. **Feature Extraction**: TF-IDF
6. **Model**: Logistic Regression
7. **Output**: Difficulty labels + score + graphs

---

## 📂 Project Structure
```text
Question-Paper-Difficulty-Analysis/
├── Question_Paper_Difficulty_Analysis.ipynb   # Main notebook
├── README.md                                  # Project documentation
├── requirements.txt                           # Python dependencies
├── data/
│   └── sample/                                # Sample question paper images
└── outputs/                                   # Generated results (auto created)
