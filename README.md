# Phish Shield 
**Malicious URL Detection using Machine Learning**

## 📌 Overview
Phish Shield is a **multi-class machine learning system** designed to detect and classify **malicious URLs** into four categories:
- Benign (Safe)
- Defacement
- Phishing
- Malware

The project analyzes URL-based lexical and structural features and applies multiple ML models to accurately classify URLs, helping improve phishing and malware detection.

---

## 🎯 Problem Statement
Malicious URLs are a major cybersecurity threat and evolve rapidly, making blacklist-based systems ineffective.  
This project aims to build a **robust ML classifier** that can generalize well to unseen URLs using feature-based learning.

---

## 🧠 Models Implemented
The following models were trained and evaluated:

- **Random Forest Classifier (Best Performer)**
- LightGBM Classifier
- XGBoost Classifier

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

##  Best Model: Random Forest
The **Random Forest classifier** achieved the best overall performance and was selected as the final model.

###  Random Forest Performance
**Accuracy:** **96.3%**

## 📈 Model Comparison

### 🔹 LightGBM
- Accuracy: **95.5%**
- Strong performance on benign and defacement URLs
- Slightly lower recall for phishing and malware classes

### 🔹 XGBoost
- Accuracy: **95.8%**
- Comparable performance to Random Forest
- Slightly weaker recall for malware detection

➡️ **Random Forest was chosen** due to its superior macro-average performance and stability across all classes.

## 🔍 Sample URL Predictions (Inference Demo)

To demonstrate real-world applicability, the trained model was tested on **previously unseen URLs**.

## 📂 Project Structure
├── Finalproject.ipynb # Jupyter notebook with full ML pipeline

├── README.md # Project documentation
