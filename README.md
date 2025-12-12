# 📊 IBM HR Analytics – Employee Attrition Analysis

## 📌 Project Overview
This project analyzes the factors that lead to employee attrition using the **IBM HR Analytics dataset**.  
The goal is to understand **why employees leave**, identify key drivers, and build a **predictive model** to help HR teams reduce attrition.

---

## 🎯 Objectives
- Perform **data cleaning** and **exploratory data analysis (EDA)**
- Identify **patterns and factors** influencing attrition
- Build **machine learning models** to predict employee attrition
- Provide **actionable insights** to help reduce employee turnover

---

## 🛠️ Tools & Technologies
- **Python**
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn
- **Jupyter Notebook**
- **Machine Learning Models**
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  

---

## 📁 Dataset
**Dataset Name:** IBM HR Analytics Employee Attrition & Performance  
**Rows:** 1470  
**Target variable:** `Attrition (Yes/No)`

---

## 🔍 Steps Performed

### **1️⃣ Data Cleaning**
- Checked for missing values  
- Handled categorical & numerical columns  
- Removed duplicates  
- Converted data types  

### **2️⃣ Exploratory Data Analysis (EDA)**
Analyzed:
- Attrition by **age**, **salary**, **department**, **job role**, **marital status**
- Relationship between attrition and **overtime**
- Impact of **education** and **experience**
- Attrition distribution across **job satisfaction** and **work-life balance**

Used visualizations (bar charts, histograms, heatmaps) for clarity.

### **3️⃣ Feature Engineering**
- Label Encoding for categorical variables  
- Feature scaling where necessary  
- Identified important features for modeling  

### **4️⃣ Model Building**
Trained models:
- Logistic Regression
- SVM
- Decision Tree  
- Random Forest  

Evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

### **5️⃣ Insights & Recommendations**
Key insights you can include based on typical results:

- Employees doing **overtime** have a significantly higher attrition rate  
- **Low salary bands** show higher turnover  
- **Younger employees** (20–35) tend to leave more  
- **Job role** and **work-life balance** impact attrition  
- Employees with **low job satisfaction** are more likely to leave  

(Replace with your actual findings if different.)

---

## 📊 Key Results
- Best-performing model: **Random Forest Classifier**  
- Achieved accuracy of around **88%**
- Identified top features influencing attrition:
  - Overtime  
  - Monthly Income  
  - Job Role  
  - Total Working Years  
  - Job Satisfaction  

---

