# 🍽️ Restaurant Risk Prediction Dashboard  

This project is part of my internship assignment where I built an end-to-end pipeline to analyze restaurant reviews, predict risk levels, and make the results explainable and interactive through a Streamlit dashboard.  

---

## 🚀 Project Overview  
The goal of this project was to:  
- Preprocess and clean raw restaurant review data.  
- Summarize reviews using **transformer-based models**.  
- Train and evaluate three ML models (**Logistic Regression, SVM, XGBoost**) on the cleaned data.  
- Compare their performance using multiple evaluation metrics.  
- Add **model explainability** (with SHAP) and a **case study for individual restaurants**.  
- Deploy an **interactive Streamlit app** that shows predictions, model explanations, and even **drift detection** for new reviews.  


## ⚙️ Tech Stack  
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Transformers** (BART for summarization)  
- **XGBoost, SVM, Logistic Regression**
- **SHAP** for explainability  
- **Streamlit** for dashboarding  

---

## 📊 Key Features  
✅ Data preprocessing & cleaning  
✅ Summarization of reviews (BART)  
✅ Model training (XGBoost, SVM, Logistic Regression)  
✅ Model comparison with metrics  
✅ SHAP-based explainability  
✅ Case study for individual restaurant predictions  
✅ Drift detection for unseen reviews  
✅ Interactive **Streamlit app**  

---

## 🖥️ Running the App  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/restaurant-risk-prediction.git
   cd restaurant-risk-prediction
   ```

2. Run the Streamlit dashboard:
    ```bash
    streamlit run app.py
    ```

## 📽️ Demo Video:
https://drive.google.com/file/d/1XlcrxRwfYMZUyz4f2EcJ24mXm1RYdZ51/view?usp=sharing


📝 Notes
- The cleaned_reviews.csv file is used for training all models after preprocessing.

- The restaurant_risk_xgb.pkl model is used for explainability in the dashboard.

- JSON metric files store accuracy/precision/recall/F1 for each model.