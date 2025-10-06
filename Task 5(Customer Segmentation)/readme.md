# 🧠 Customer Segmentation using K-Means Clustering

## 🎯 Objective
To segment mall customers based on their spending behavior and income using **K-Means clustering**, helping businesses design targeted marketing strategies.

---

## 📊 Dataset Overview
**Dataset:** Mall Customers  
**Features:** CustomerID, Gender, Age, Annual Income (k$), Spending Score (1–100)

---

## 🧹 Data Preprocessing
- Checked and handled missing values  
- Encoded categorical feature “Gender”  
- Scaled numerical columns using `StandardScaler`

---

## 🔍 Exploratory Data Analysis (EDA)
- Visualized distributions of Age, Income, and Spending Score  
- Analyzed income–spending trends by gender  
- Identified patterns showing diverse customer behaviors

---

## ⚙️ Model Development
- Applied **K-Means Clustering**  
- Determined optimal clusters (k=5) using **Elbow Method**  
- Assigned customers to clusters representing behavioral segments

---

## 📈 Results & Insights
| Cluster | Description | Strategy |
|----------|--------------|-----------|
| 0 | High Income – High Spending | Premium offers |
| 1 | Low Income – Low Spending | Discounts |
| 2 | Young & High Spending | Trend campaigns |
| 3 | High Income – Low Spending | Loyalty programs |
| 4 | Average Income – Moderate Spending | Combo offers |

---

## 📊 Visualizations
- Elbow plot for k selection  
- 2D cluster visualization using PCA and t-SNE  

---

## 🧩 Conclusion
The K-Means model successfully identified 5 meaningful customer groups, enabling **personalized marketing** and **data-driven business strategies**.
