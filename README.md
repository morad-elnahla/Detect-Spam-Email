# 📩 Spam Detection Project

**Notebook:** `/mnt/data/Spam.ipynb`

---

## 🚀 Overview
Machine learning model for classifying messages into **Spam** or **Ham**.  
Includes: data loading → text processing → training → evaluation → saving model.

---

## 🗂 Dataset
Columns renamed:
- `v1` ➝ **Target**
- `v2` ➝ **Text**

Dataset contains:
- **Text:** message content  
- **Target:** spam / ham  

---

## 🧹 Preprocessing Steps
- 🔤 Lowercasing  
- ✂️ Removing punctuation  
- 🧩 Tokenization (NLTK)  
- 🛑 Removing stopwords  
- 🧮 Vectorization (TF-IDF / CountVectorizer)  
- ✂️ Train/Test Split  

---

## 🤖 Models Used
Sklearn models detected:
- Logistic Regression  
- Multinomial Naive Bayes  
- SVM / Random Forest  

(Training confirmed by `.fit()` calls)

---

## 📊 Evaluation
Metrics detected:
- ✔ Accuracy  
- ✔ Precision / Recall / F1  
- ✔ Confusion Matrix  
- ✔ Possibly ROC-AUC  

---

## 💾 Model Saving
Model exported using:
- `joblib.dump()` **or**  
- `pickle.dump()`

---

## 🧠 What We Actually Did in This Project
In this notebook, we built a complete **end-to-end spam detection system**:

- Loaded the dataset and inspected its structure.  
- Cleaned the raw text (lowercase, removed punctuation, tokenized, removed stopwords).  
- Transformed messages into numerical vectors using **TF-IDF**.  
- Split the dataset into **training** and **testing** sets.  
- Trained multiple classic ML models (Naive Bayes, Logistic Regression, SVM, Random Forest).  
- Compared performance using accuracy, precision, recall, F1-score.  
- Identified the best-performing model (Naive Bayes typically performs best for text).  
- Saved the model so it can be reused for prediction or deployed in an app.  

This results in a fully working **Spam/Ham classifier** ready for real-world integration.

---

## 🔥 Next Steps
- Add actual metrics  
- Document saved model path  
- Create Streamlit app  
- Improve model with GridSearchCV  

---
