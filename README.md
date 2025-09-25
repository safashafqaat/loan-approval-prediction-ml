# Loan Approval Prediction 🏦

This project predicts **loan approval status** using Machine Learning techniques on the Kaggle Loan Approval dataset.  
The goal is to build a reliable model that can classify whether a loan application will be **Approved** or **Rejected** based on applicant details.  

---

##  Project Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Scaled numerical features

2. **Exploratory Data Analysis**
   - Visualized distributions and outliers
   - Analyzed categorical feature balance (Education, Employment, etc.)
   - Plotted boxplots and histograms for numerical features

3. **Modeling**
   - Implemented **Logistic Regression** and **Decision Tree Classifier**
   - Evaluated performance on **imbalanced data**
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance classes
   - Compared results **before and after SMOTE**

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

- Logistic Regression achieved strong baseline performance with balanced metrics  
- Decision Tree outperformed Logistic Regression with higher accuracy and F1-score  
- Minimal change after SMOTE since dataset was moderately balanced (~62:38), but included for demonstration  

---

##  Project Structure

Loan-Approval-Prediction/
│── Loan_Approval_Prediction.ipynb   # Jupyter Notebook with full code
│── loan_approval_dataset.csv        # Dataset (from Kaggle)
│── requirements.txt                 # Project dependencies
│── README.md                        # Project documentation


