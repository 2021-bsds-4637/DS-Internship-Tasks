## 🏦 Task 4 – Bank Marketing Prediction  

### 🎯 Objective  
Predict whether a bank client will subscribe to a term deposit (`yes` or `no`) based on client and campaign data.  

### 🧠 Approach  
- Preprocessed data (encoding, scaling, feature engineering).  
- Trained **Logistic Regression** and **Random Forest** models.  
- Evaluated using accuracy, F1-score, and ROC-AUC.  
- Used **LIME** for model explainability.  

### 📊 Results & Insights  
- **Random Forest** achieved the best performance (Accuracy ≈ 0.89, ROC-AUC ≈ 0.79).  
- Key influential features: **contact method**, **poutcome**, **campaign**, and **month**.  
- LIME analysis showed clear feature impact on individual predictions.  
