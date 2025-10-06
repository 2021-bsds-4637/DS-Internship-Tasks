# **Task 7 – Loan Default Risk Prediction**

## **📘 Problem Statement and Objective**
The objective of this task is to predict the likelihood of a borrower defaulting on a loan. By identifying risky applicants in advance, financial institutions can minimize potential losses and make data-driven lending decisions.  
The goal is to build a machine learning model that classifies whether a loan will be repaid (0) or defaulted (1).

---

## **📊 Dataset Description**
The dataset contains information about borrowers, including demographic, financial, and credit-related features.  
Key columns include:
- **loan_amnt** – Loan amount applied by the borrower  
- **term** – Duration of the loan  
- **int_rate** – Interest rate charged  
- **installment** – Monthly installment  
- **grade, sub_grade** – Loan quality indicators  
- **emp_length** – Employment length  
- **home_ownership, annual_inc, purpose** – Applicant’s personal and financial data  
- **loan_status** – Target variable (0 = Fully Paid, 1 = Default)

---

## **🧹 Data Cleaning and Preprocessing**
Steps performed:
1. Handled missing values using **SimpleImputer (mean/most_frequent)**  
2. Converted categorical variables using **OneHotEncoder**  
3. Standardized numeric columns with **StandardScaler**  
4. Split the data into **train (80%)** and **test (20%)** sets  
5. Removed redundant or highly correlated columns  
6. Handled class imbalance using **threshold tuning and cost-based evaluation**

---

## **🔍 Exploratory Data Analysis (EDA)**
EDA included:
- Distribution of target variable (default vs. non-default)  
- Correlation heatmap between numeric features  
- Boxplots for loan amount vs. loan status  
- Countplots for categorical variables such as `purpose`, `grade`, and `home_ownership`  
- **Insights:** Higher interest rates and lower grades are associated with higher default probability.

---

## **🤖 Model Building and Evaluation**
Models implemented:
- **Logistic Regression**
- **Decision Tree Classifier**

Evaluation metrics used:
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC Curve  

Threshold tuning was applied to analyze business costs for false positives (FP) and false negatives (FN).
