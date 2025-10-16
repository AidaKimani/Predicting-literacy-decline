# Predicting-literacy-decline
Predicting Literacy Decline Among Gen Alpha 

### Using Machine Learning to Identify Students at Risk of Literacy Decline  

---

## 📚 Project Overview  

This project explores the growing concern of **literacy decline among Generation Alpha**, focusing on reading comprehension, vocabulary, and sustained attention.  
Despite widespread access to digital learning tools, increased screen time and short-form content exposure are reducing engagement with traditional reading materials.  

The study applies **machine learning** to predict students at risk of literacy decline by integrating **academic performance** and **behavioral indicators** such as screen time, engagement, and adaptability.  
Models including **Logistic Regression** and **Random Forest Classifier** are trained and evaluated on precision, recall, and accuracy metrics.  

---

## 🎯 Objectives  

- Combine behavioral and academic indicators to predict literacy risk.  
- Build baseline and advanced machine learning models for risk classification.  
- Identify the most influential factors driving literacy decline.  
- Provide insights to support early intervention and policy planning.  

---

## 🧠 Methodology Summary  

### Data Sources  
- **Kaggle:** Public education and literacy datasets (2018–2024)  
- ~10,000 student records (subset of 1,000 used for testing)  
- 20–30 features including:  
  - Screen time  
  - Reading habits  
  - Engagement metrics  
  - Household income  
  - Literacy scores (pre- and post-training)  

**Target Variable:** `Overall_Literacy_Score` → converted to binary:  
`Literacy_Risk` (1 = at risk, 0 = not at risk)  

---

### Modeling  
- **Baseline:** Logistic Regression  
- **Improved Model:** Random Forest Classifier (future tuning planned)  
- **Planned Models:** XGBoost, Neural Networks  

---

### Evaluation Metrics  
- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  

---

## 📊 Key Results  

| Model | Accuracy | Precision | Recall |
|--------|-----------|------------|--------|
| **Logistic Regression** | 90% | 100% | 67% |
| **Random Forest** | 80% | 80% | 44% |

🧩 **Insights**  
- Post-training literacy scores improved from ~25 → ~60.  
- Medium engagement levels correlated with higher literacy outcomes.  
- Low-income and rural participants showed lower average literacy.  
- Key predictors: Post_Training_Basic_Computer_Knowledge_Score, Modules_Completed, Quiz_Performance.  

---

## 🖼️ Visual Results  

Key figures from the analysis include:  
- `literacy_hist.png` — Distribution of pre- and post-training literacy scores  
- `corr_matrix.png` — Correlation heatmap of academic and behavioral factors  
- `feature_importance.png` — Feature importance from Random Forest model  
- `confusion_matrix.png` — Model performance visualization  

---
