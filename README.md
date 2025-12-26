# Loan-Sancation-EDA
“Exploratory Data Analysis on Loan Sanction Dataset”

# 📊 Loan Sanction Dataset | Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Loan Sanction dataset containing 614 records and 13 features.  
The goal is to uncover patterns behind loan approvals and rejections, handle missing values, and identify key predictors for loan sanction decisions.

---

## 🎯 Problem Statement
Financial institutions often face challenges in loan approvals due to:
- Fragmented applicant data
- Missing values and inconsistencies
- Imbalanced approval records

This project applies **EDA techniques** to clean, preprocess, and analyze loan sanction data, enabling better insights into applicant credibility and loan approval trends.

---

## 🗂️ Dataset Details
- **Records:** 614 applicants  
- **Features:** 13 (8 categorical, 5 numerical)  
- **Target Variable:** Loan Status (Approved/Rejected)

**Columns include:**
- Loan ID, Gender, Married, Dependents, Education, Self Employed  
- Applicant Income, Co‑applicant Income, Loan Amount, Loan Term  
- Credit History, Property Area, Loan Status  

---

## 🛠️ Preprocessing Techniques
- ✔ Handling Missing Values (Mode for categorical, Median for numerical)  
- ✔ Data Type Conversion (`Dependents` → integer)  
- ✔ Outlier detection in income & loan amount  
- ✔ Encoding categorical variables for analysis  

---

## 📊 Analysis & Insights

### 🔹 Univariate Analysis
- Applicant Income & Loan Amount show **right‑skewed distributions** with extreme outliers  
- Majority of applicants are **male** and from **semi‑urban areas**  
- Most applicants have a **positive credit history**, strongly linked to approvals  

### 🔹 Bivariate Analysis
- **Credit History** is the most powerful predictor of loan approval  
- Higher combined applicant + co‑applicant income increases approval chances  
- Married applicants and graduates show slightly higher approval rates  
- Rural applicants have fewer approvals compared to urban/semi‑urban  

### 🔹 Multivariate Analysis
- Income correlates moderately with loan amount requests  
- Loan approvals overlap across income ranges → income alone doesn’t decide approval  
- Credit history dominates as the deciding factor  

---

## ✅ Conclusion
- Loan approval is primarily driven by **credit history**, followed by **income** and **property area**  
- Demographic features (education, marital status, employment type) play a secondary role  
- Proper handling of missing values, outliers, and class imbalance is essential for reliable predictive modeling  

---

## 🛠️ Tools Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 🤝 Collaboration
Developed with **# 📊 Loan Sanction Dataset | Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Loan Sanction dataset containing 614 records and 13 features.  
The goal is to uncover patterns behind loan approvals and rejections, handle missing values, and identify key predictors for loan sanction decisions.

---

## 🎯 Problem Statement
Financial institutions often face challenges in loan approvals due to:
- Fragmented applicant data
- Missing values and inconsistencies
- Imbalanced approval records

This project applies **EDA techniques** to clean, preprocess, and analyze loan sanction data, enabling better insights into applicant credibility and loan approval trends.

---

## 🗂️ Dataset Details
- **Records:** 614 applicants  
- **Features:** 13 (8 categorical, 5 numerical)  
- **Target Variable:** Loan Status (Approved/Rejected)

**Columns include:**
- Loan ID, Gender, Married, Dependents, Education, Self Employed  
- Applicant Income, Co‑applicant Income, Loan Amount, Loan Term  
- Credit History, Property Area, Loan Status  

---

## 🛠️ Preprocessing Techniques
- ✔ Handling Missing Values (Mode for categorical, Median for numerical)  
- ✔ Data Type Conversion (`Dependents` → integer)  
- ✔ Outlier detection in income & loan amount  
- ✔ Encoding categorical variables for analysis  

---

## 📊 Analysis & Insights

### 🔹 Univariate Analysis
- Applicant Income & Loan Amount show **right‑skewed distributions** with extreme outliers  
- Majority of applicants are **male** and from **semi‑urban areas**  
- Most applicants have a **positive credit history**, strongly linked to approvals  

### 🔹 Bivariate Analysis
- **Credit History** is the most powerful predictor of loan approval  
- Higher combined applicant + co‑applicant income increases approval chances  
- Married applicants and graduates show slightly higher approval rates  
- Rural applicants have fewer approvals compared to urban/semi‑urban  

### 🔹 Multivariate Analysis
- Income correlates moderately with loan amount requests  
- Loan approvals overlap across income ranges → income alone doesn’t decide approval  
- Credit history dominates as the deciding factor  

---

## ✅ Conclusion
- Loan approval is primarily driven by **credit history**, followed by **income** and **property area**  
- Demographic features (education, marital status, employment type) play a secondary role  
- Proper handling of missing values, outliers, and class imbalance is essential for reliable predictive modeling  

---

## 🛠️ Tools Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 🤝 Collaboration
Developed with **P. Greeshma,I. Lalitha, A. Priya,**  
Grateful to Lakshmi Teja Illuri Mam, Program Manager Raghu Ram Aduri Sir, Placement Officer Sigilipelli Yeshwanth Sir, and Innomatics Research Labs for their guidance. 

---


## 🔖 Hashtags
#EDA #DataAnalysis #Python #MachineLearning #DataScience #LoanPrediction #FinancialAnalytics #Pandas #Seaborn #Matplotlib #PortfolioProjects #CareerGrowth
