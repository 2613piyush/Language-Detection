# 🌍 Language Detection Using Machine Learning and NLP

A powerful Machine Learning and Natural Language Processing (NLP) project that automatically detects the language of a given text. This project is trained on multilingual data and can accurately identify languages such as English, Hindi, French, Spanish, German, and many more.

---

## 🚀 Project Overview

Language detection is a core problem in Natural Language Processing (NLP). This project uses text preprocessing, feature extraction, and a machine learning classification model to predict the language of any input text.

This project demonstrates:

- ✅ Data Cleaning and Preprocessing
- ✅ Natural Language Processing (NLP)
- ✅ Feature Extraction
- ✅ Machine Learning Model Training
- ✅ Model Evaluation
- ✅ Real-Time Language Prediction
- ✅ Model Serialization

---

## 🧠 Technologies Used

- Python
- Machine Learning
- Natural Language Processing (NLP)
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Pickle

---

## 📂 Dataset Information

The dataset contains thousands of text samples from different languages. Each record includes:

- **Text** → Sentence or phrase in a specific language
- **Language** → Corresponding language label

### Example

| Text | Language |
|------|----------|
| Hello, how are you? | English |
| नमस्ते, आप कैसे हैं? | Hindi |
| Bonjour, comment allez-vous? | French |
| Hola, ¿cómo estás? | Spanish |

---
## 📁 Project Structure

Language-Detection-Using-ML-NLP/
│
├── data/
│   └── Language Detection.csv
│
├── notebooks/
│   └── language detection.ipynb
│
├── models/
│   └── language_detection_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE


## ⚙️ Machine Learning Workflow

### 1️⃣ Data Loading
- Load the CSV dataset into a Pandas DataFrame.

### 2️⃣ Data Cleaning
- Remove punctuation, symbols, and unnecessary characters.
- Convert text to lowercase.

### 3️⃣ Feature Extraction
- Convert text into numerical vectors using NLP techniques.

### 4️⃣ Train-Test Split
- Split the dataset into training and testing sets.

### 5️⃣ Model Training
- Train a classification model using Scikit-learn.

### 6️⃣ Model Evaluation
- Evaluate model performance and accuracy.

### 7️⃣ Prediction
- Detect the language of custom user input.

### 8️⃣ Model Saving
- Save the trained model using Pickle.

---

## 📊 Libraries Used

```python
pandas
numpy
re
string
sklearn
pickle
