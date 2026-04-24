# 🚀 Credit Card Fraud Detection (End-to-End ML Project)

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.
The goal is to build a reliable system that can identify fraud with high recall while maintaining strong precision, which is critical in financial systems.

---

## 🎯 Problem Statement

Credit card fraud is a major issue in the financial industry, leading to significant monetary losses.
The challenge lies in:

* Highly imbalanced dataset
* Need to maximize fraud detection (recall)
* While minimizing false alarms (precision)

👉 Objective:
Build a model that can accurately detect fraudulent transactions in real-time.

---

## 💡 Solution Approach

* Data preprocessing
* Model training
* Evaluation using performance metrics
* Explainability using SHAP
* Risk-based transaction analysis

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* SHAP
* Jupyter Notebook
* EDA (Exploratory Data Analysis)

---

## 📊 Dataset Information

* Total Transactions: 284,000+
* Dataset is highly imbalanced
* Features are anonymized using PCA transformation (V1–V28)
* Includes:

  * Time
  * Amount
  * Class (0 = Normal, 1 = Fraud)

📌 Dataset Link:
https://www.kaggle.com/datasets/isaikumar/creditcardfraud

---

## ⚙️ Model Development (main.ipynb)

* Data preprocessing
* Model training
* Evaluation metrics:

  * Recall
  * Precision
  * Confusion Matrix

### 📈 Model Performance

* Recall: 80.6%
* Precision: 94.0%

---

## 🔍 Insights & Analysis (insights.ipynb)

* SHAP analysis
* Risk-based transaction analysis
* Threshold-based evaluation
* Fraud pattern understanding

---

## 🧠 Key Business Insights

* Prioritizing recall is critical in fraud detection
* Risk-based classification improves decision-making
* Model can be integrated into:

  * Real-time fraud detection systems
  * Banking security pipelines
  * Transaction monitoring tools

---

## 📁 Project Structure

```
credit-card-fraud-detection/
│
├── main.ipynb              
├── insights.ipynb          
├── fraud_model.pkl         
├── README.md               
```

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Real-time deployment (Flask / API)
* Handling concept drift

---

## ⭐ Conclusion

This project demonstrates a complete workflow from data preprocessing to business insights.
The model is optimized for real-world impact, ensuring maximum fraud detection with minimal false alarms.

---

⭐ If you found this useful, consider giving a star!
