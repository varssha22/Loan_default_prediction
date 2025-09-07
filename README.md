# Loan Default Prediction – Lending Club Dataset  

## 🎯 Problem-Solution Highlights  

**Problem:**  
Financial institutions face challenges in managing **credit risk**. Borrowers who default can cause financial losses, reduced profitability, and increased risk exposure. Traditional manual assessments are slow, inconsistent, and not scalable for large datasets (200,000+ loans).  

**Solution:**  
- Built a **data-driven model** to predict loan defaults using the Lending Club dataset.  
- Performed **data cleaning, feature engineering, and EDA** to identify key risk factors.  
- Trained multiple **ML models** (LR, DT, RF, XGBoost) achieving **99%+ accuracy**.  
- Created an **interactive Power BI dashboard** for monitoring loan performance and insights.  

**Impact:**  
- Early identification of high-risk borrowers reduces defaults.  
- Business-friendly dashboard supports decision-making.  
- Scalable solution for large datasets with actionable insights.

---

## 📌 Project Overview  

This project focuses on predicting **loan defaults** using the **Lending Club dataset** from Kaggle, which contains **200,000+ rows** and **150+ features**.  
The project addresses credit risk management challenges, aiming to reduce defaults, improve lending decisions, and provide actionable insights to business users.

---

## 🔧 Key Steps  

### 1. Data Preprocessing  
- Handled missing values through imputation.  
- Removed redundant/irrelevant features.  
- Addressed multicollinearity among variables.  
- Applied feature engineering to create meaningful variables.

### 2. Exploratory Data Analysis (EDA)  
- Visualized distributions, correlations, and outliers.  
- Identified key risk factors influencing loan default.  
- Summarized trends using graphs and pivot tables.

### 3. Machine Learning Models  
Implemented and compared multiple models:  
- Logistic Regression (LR)  
- Decision Tree (DT)  
- Random Forest (RF)  
- XGBoost (XGB)  

📊 **Achieved 99% accuracy on the test set.**

### 4. Dashboard – Power BI  
- Created an interactive dashboard to visualize loan data.  
- Included borrower profiles, loan performance trends, default risk factors, and key KPIs.  
- Made results accessible to business users for decision-making.

---

## 🚀 Results & Insights  

- **XGBoost** outperformed the other models with **99.85% Average CV score (Recall)** and **100% Accuracy**.  
- **Top risk factors** (from Logistic Regression weights):  
  - **recoveries** → Amount recovered after the loan was charged-off.  
  - **total_pymnt** → Total payment (principal + interest + fees) received.  
  - **loan_amnt** → Total loan amount applied for.  
  - **out_prncp** → Outstanding principal (remaining unpaid loan balance).  
  - **total_rec_int** → Total interest received to date.  
- Interactive **Power BI dashboard** enables monitoring of loan performance and defaults.

---

## 📊 Tools & Technologies  
- **Python**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Power BI**: Dashboard creation & reporting  
- **Jupyter Notebook**: EDA & experimentation  

---

## 📈 Future Work  
- Hyperparameter tuning with cross-validation.  
- Model deployment using Flask or Streamlit.  
- Integrating real-time data pipelines.  

---

## 📖 References  
- [Lending Club Dataset – Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club/discussion?sort=hotness)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable)  
- [XGBoost Documentation](https://xgboost.readthedocs.io)  
- [Power BI Documentation](https://learn.microsoft.com/en-us/power-bi)  

---

## 📬 Contact  
🐙 [GitHub](https://github.com/varssha22)
