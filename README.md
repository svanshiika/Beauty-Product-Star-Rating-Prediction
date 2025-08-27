# Beauty Product Star Rating Prediction ⭐

Predicting **Amazon beauty product star ratings** (low / medium / high) using **LIWC-like NLP features** and supervised ML models.

---

## 📌 Project Overview
This project explores consumer behavior in the beauty industry by analyzing Amazon review text and predicting the corresponding star rating category.  
The pipeline includes:
- Data preprocessing & cleaning
- LIWC-inspired feature engineering (emotions, cognition, social words, etc.)
- Model training (Logistic Regression, KNN, Random Forest)
- Evaluation with cross-validation, hyperparameter tuning, and SMOTE oversampling.

Random Forest was found to be the best-performing model in this study.

---

## 🗂️ Repo Structure

├── notebooks/ # Jupyter notebooks for exploration & modeling
├── src/ # Python scripts for data prep, feature extraction, training
├── data/ # (Optional) sample dataset or link to source
├── reports/ # Final report PDF
├── requirements.txt # Dependencies
└── README.md # This file


---

## 📊 Results
- Logistic Regression: moderate performance, sensitive to class imbalance  
- KNN: struggled with non-linear LIWC features  
- **Random Forest**: most robust, best F1-score across evaluations  

---

## ⚙️ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Beauty-Product-Star-Rating-Prediction.git
   cd Beauty-Product-Star-Rating-Prediction
