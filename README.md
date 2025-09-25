# Loan Approval Prediction 🏦

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/) 
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.5-orange)](https://scikit-learn.org/stable/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This project predicts **loan approval status** using Machine Learning techniques on the Kaggle Loan Approval dataset.  
The objective is to help financial institutions make **faster and data-driven decisions** on whether a loan application should be **Approved** or **Rejected**.  

---

## Project Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Scaled numerical features

2. **Exploratory Data Analysis**
   - Visualized distributions & outliers
   - Analyzed categorical features (Education, Employment, etc.)
   - Boxplots and histograms for numerical features

3. **Modeling**
   - Implemented **Logistic Regression** and **Decision Tree**
   - Evaluated models on **imbalanced data**
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)**
   - Compared results **before & after balancing**

4. **Evaluation**
   - Confusion Matrix & Heatmaps
   - Precision, Recall, and F1-score
   - ROC Curve and AUC

---

## Tech Stack

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Seaborn, Matplotlib**
- **Imbalanced-learn (SMOTE)**

---

##  Results

| Model                   | Data Type       | Precision | Recall | F1-Score | Accuracy |
|--------------------------|----------------|-----------|--------|----------|----------|
| Logistic Regression      | Imbalanced     | 0.9551    | 0.9209 | 0.9377   | 92.3%    |
| Logistic Regression      | SMOTE          | 0.9515    | 0.9228 | 0.9369   | 92.2%    |
| Decision Tree            | Imbalanced     | 0.9776    | 0.9868 | 0.9822   | 97.7%    |
| Decision Tree            | SMOTE          | 0.9776    | 0.9849 | 0.9812   | 97.6%    |

> ✅ Decision Tree achieved the highest performance, while Logistic Regression provided a strong baseline.  
> ⚠️ Minimal difference between SMOTE and Imbalanced dataset results, since dataset was already moderately balanced (~62:38).

---

##  Project Structure

Loan-Approval-Prediction/
│── Loan_Approval_Prediction.ipynb   # Jupyter Notebook with full code
│── loan_approval_dataset.csv        # Dataset (from Kaggle)
│── requirements.txt                 # Project dependencies
│── README.md                        # Project documentation


