# 🩺 Stroke Diagnosis Prediction using Random Forest & NLP

This project builds a **machine learning pipeline** that predicts a patient's diagnosis based on their **demographic, medical, and symptom data**.  
It combines **data preprocessing, natural language processing (NLP)** for symptom text, **feature engineering**, and a **Random Forest classifier**.

---

## 📌 Features
- **Data Cleaning** – Handles missing values, extracts numerical features from text fields.  
- **Feature Engineering** – Extracts HDL & LDL values from cholesterol data, splits blood pressure readings.  
- **Categorical Encoding** – Converts categorical features to numeric using `LabelEncoder`.  
- **Text Preprocessing (NLP)** – Lemmatizes symptoms text using `spaCy`, removes stopwords & punctuation.  
- **TF-IDF Vectorization** – Converts preprocessed symptoms into numerical features.  
- **Machine Learning Model** – Trains a `RandomForestClassifier` to predict stroke diagnosis.  
- **Train/Test Split** – Uses an 80/20 split for model evaluation.

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Pandas, NumPy** – Data handling  
- **Matplotlib** – (Optional) Visualization  
- **scikit-learn** – Label encoding, TF-IDF vectorization, train-test split, model training  
- **spaCy** – NLP for symptom preprocessing  
- **Random Forest Classifier** – Final prediction model

---

