# ⭐ Beauty Product Star Rating Prediction

A machine learning project that predicts **Amazon beauty product star ratings (low / medium / high)** from customer reviews using **LIWC-like NLP features**.  

Built with **Python (scikit-learn, NLTK, imbalanced-learn)** and **WEKA**, this project explores consumer behavior in the beauty industry and benchmarks classic ML algorithms.

---

## 📌 Project Overview
- **Goal**: Predict star rating classes (1–2 = low, 3 = medium, 4–5 = high) from review text.  
- **Features**: LIWC-inspired features (affective, cognitive, social, moralization words, etc.).  
- **Models**: Logistic Regression, K-Nearest Neighbors (KNN), Random Forest.  
- **Tools**: Python (Jupyter, Spyder) + WEKA (GUI-based ML).  

Random Forest emerged as the most robust model overall.

---

## 📂 Repository Structure
'''
├─ notebooks/
│ ├─ Logistic Regression (CA2).ipynb
│ ├─ K-Nearest Neighbors (CA2).ipynb
│ └─ Random Forest (CA2).ipynb
├─ data/
│ └─ ml_model_dataset_FINAL_FIXED.arff
├─ reports/
│ ├─ VSharma_CA2_Report.pdf
│ └─ WEKA(Screenshots_of_results).docx
├─ requirements.txt
├─ .gitignore
└─ README.md
'''

---

## 📊 Results

### Python (scikit-learn)
- Logistic Regression: struggled on imbalance; improved after SMOTE + tuning.  
- KNN: sensitive to imbalance, best with **k=11 neighbors**.  
- Random Forest: consistently best, highest F1 and ROC-AUC.  

### WEKA
- Random Forest achieved **F1 ≈ 0.68** (best among all).  
- Logistic Regression and KNN improved under cross-validation but lagged behind RF.  

Screenshots of WEKA results are included in `reports/`.

---

## ✉️ Contact
If you have questions, feedback, or collaboration ideas, feel free to reach out:  
- Email: [svanshiika@gmail.com](mailto:svanshiika@gmail.com)  
- LinkedIn: [vanshika](https://www.linkedin.com/in/your-profile/svanshiika21)
