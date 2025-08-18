# 🩺 Diabetes Prediction using Machine Learning  

## 📌 Project Overview  
This project applies **Machine Learning models** to the **PIMA Indians Diabetes Dataset** to predict whether a patient has diabetes based on diagnostic features.  
We focus on **Logistic Regression** and **K-Nearest Neighbors (KNN)** as the core classification algorithms.  

---

## 🎯 Objectives  
- Explore the dataset to understand patterns related to diabetes.  
- Build and compare **Logistic Regression** and **KNN models**.  
- Evaluate model performance using key classification metrics.  
- Provide a reliable baseline for future predictive healthcare systems.  

---

## 🛠️ Tools & Technologies  
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook

---

## 🔎 Key Steps  

### 1. Data Preprocessing  
- Checked for missing/zero values.  
- Normalized numerical features.  
- Split data into **train** and **test** sets.  

### 2. Exploratory Data Analysis (EDA)  
- Visualized distributions of glucose, BMI, and age.  
- Examined correlations between features and diabetes outcome.  

### 3. Model Development  
- **Logistic Regression:** baseline linear model.  
- **K-Nearest Neighbors (KNN):** tested different values of *k* to optimize performance.  

### 4. Model Evaluation  
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-score  
- ROC Curve & AUC  

---

## ✅ Results & Insights  
- **Logistic Regression:**  
  - Accuracy ~ **78%**  
  - Performed well in identifying diabetic patients.  

- **K-Nearest Neighbors (k=7):**  
  - Accuracy ~ **75%**  
  - Slightly weaker on recall compared to Logistic Regression.  

📌 **Insight:** Logistic Regression provided better overall performance on this dataset, while KNN was more sensitive to parameter tuning and feature scaling.  
