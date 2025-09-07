# Loan Default Prediction – Lending Club Dataset
<h1> 📌 Project Overview </h1>

This project focuses on predicting loan defaults using the Lending Club dataset from Kaggle, which contains 200,000+ rows and 150+ features.
The goal was to build a machine learning pipeline that performs data cleaning, feature engineering, exploratory data analysis (EDA), and model training, followed by creating an interactive dashboard in Power BI for business insights.

🔧 Key Steps
1. Data Preprocessing

Handled missing values through imputation.

Removed redundant/irrelevant features.

Addressed multicollinearity among variables.

Applied feature engineering to create meaningful variables.

2. Exploratory Data Analysis (EDA)

Visualized distributions, correlations, and outliers.

Identified key risk factors influencing loan default.

Summarized trends using graphs and pivot tables.

3. Machine Learning Models

Implemented and compared multiple models:

Logistic Regression (LR)

Decision Tree (DT)

Random Forest (RF)

XGBoost (XGB)

📊 Achieved 99% accuracy on the test set.

4. Dashboard – Power BI

Created an interactive dashboard to visualize loan data.

Included borrower profiles, loan performance trends, default risk factors, and key KPIs.

Made results accessible to business users for decision-making.

📂 Project Structure
├── data/                  # Dataset (not uploaded due to size/Kaggle policy)
├── notebooks/             # Jupyter notebooks for EDA, preprocessing, and modeling
├── scripts/               # Python scripts for pipeline automation
├── dashboard/             # Power BI file (.pbix)
├── results/               # Model results, plots, metrics
├── README.md              # Project documentation

🚀 Results & Insights

Random Forest and XGBoost outperformed baseline models.

Top risk factors for default: interest rate, annual income, loan grade, debt-to-income ratio.

Business-friendly dashboard for monitoring loan performance and defaults.

📊 Tools & Technologies

Python: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

Power BI: Dashboard creation & reporting

Jupyter Notebook: EDA & experimentation

📈 Future Work

Hyperparameter tuning with cross-validation.

Model deployment (Flask/Streamlit).

Integrating real-time data pipelines.

📬 Contact

👩‍💻 Developed by [Your Name]
📧 Email: [Your Email]
🔗 LinkedIn: [Your LinkedIn]
