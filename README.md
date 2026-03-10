# 📊 Employee Attrition Analysis

Employee attrition is a critical challenge for organizations as it affects productivity, increases recruitment costs, and impacts team stability.  
This project analyzes HR employee data to identify the key factors that contribute to employees leaving an organization.

The goal of this project is to understand how **demographics, job roles, compensation, work experience, and employee satisfaction** influence attrition and to generate insights that help improve employee retention.

---

## 📁 Dataset Overview

- **Total Records:** 2,925 employees  
- **Total Features:** 37 columns  

The dataset contains employee information including demographics, job roles, compensation details, work experience, and satisfaction levels.

---

## 📌 Key Feature Categories

### 👤 Demographics
- Age  
- Gender  
- Marital Status  
- Education  
- Education Field  

### 💼 Job Information
- Job Role  
- Job Level  
- Department  
- Business Travel  
- Over Time  

### 💰 Compensation
- Monthly Income  
- Hourly Income  
- Monthly Rate  
- Percent Salary Hike  
- Stock Option Level  

### 😊 Satisfaction Metrics
- Job Satisfaction  
- Environment Satisfaction  
- Relationship Satisfaction  
- Work Life Balance  

### 📈 Work Experience
- Total Working Years  
- Years At Company  
- Years In Current Role  
- Years Since Last Promotion  
- Number of Companies Worked  

---

## 📂 Project Files

**Employee_Attrition_Analysis_Dataset.xlsx**  
Raw dataset containing employee information.

**Employee_Attrition_Analysis_Solution.xlsx**  
Cleaned dataset with analysis across multiple sheets.

---

## 🧹 Data Cleaning Steps

To ensure accurate analysis, the following steps were performed:

- Removed duplicate rows based on **Employee Number**
- Filled missing categorical values such as Department, Gender, and Job Role with **"Unknown"**
- Replaced missing numerical values like Age and Monthly Income with **median or mean values**
- Filled missing satisfaction scores using median values
- Standardized the **Attrition column**
- Created additional columns such as **Income Band** and **Daily Rate**

---

## 📊 Analysis Performed

The project includes analysis across multiple dimensions:

- Attrition by **Job Role and Department**
- Impact of **Overtime on Employee Attrition**
- Attrition by **Age, Gender, and Marital Status**
- Attrition by **Work Experience and Tenure**
- Attrition based on **Job Satisfaction and Work Life Balance**
- Attrition trends based on **Income and Salary Growth**

---

## 🛠️ Tools & Technologies Used

- Microsoft Excel  
- Python  
- Pandas  
- OpenPyXL  

---

## 🎯 Project Objective

The objective of this project is to analyze HR data and identify the main factors contributing to employee attrition.  
The insights from this analysis can help organizations make **data-driven decisions to improve employee retention and workplace satisfaction.**

