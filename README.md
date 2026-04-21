# 📊 Insurance Cost Analysis (EDA)

## 🔍 Problem Statement
ABC Insurance maintains a dataset of policyholders containing demographic, lifestyle, and medical information. 
The company wanted to understand which factors most influence medical insurance premiums in order to improve pricing 
strategy and risk assessment.
Medical costs vary significantly across individuals. Factors such as smoking habits, age, and body mass index (BMI) are 
believed to strongly affect insurance charges. The objective of this analysis is to validate these assumptions using data.

---

## 🎯 Objective
To perform Exploratory Data Analysis (EDA) on the insurance dataset and identify key drivers of medical insurance charges. 
The insights can later support the development of a predictive model for insurance cost estimation.

---

## 🧰 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📁 Dataset Overview
The dataset contains 1,338 records and 7 features:

- age: Age of the policyholder  
- sex: Gender  
- bmi: Body Mass Index (health indicator)  
- children: Number of dependents  
- smoker: Smoking status  
- region: Residential region  
- charges: Medical insurance cost (target variable)  

---

## 🧹 Data Exploration & Cleaning
- Imported and loaded dataset using Pandas  
- Checked dataset shape and data types  
- Verified missing values (none found)  
- Confirmed dataset was clean and ready for analysis  

### Observations:
- Dataset contains 1,338 rows and 7 columns  
- No missing values were detected  

---

## 📊 Exploratory Data Analysis

### 1. Categorical Feature Analysis
Count plots were used to understand distribution across categories such as sex, smoker status, region, and number of children.

### Observations:
- Gender distribution is nearly balanced  
- Smokers form a smaller proportion of the dataset  
- Region distribution is relatively even  

---

### 2. Numerical Feature Analysis
Scatter plots were used to study relationships between age, BMI, and insurance charges.

### Observations:
- Insurance charges increase with age  
- Higher BMI values are associated with higher charges  
- Smokers consistently show significantly higher costs  

---

### 3. Feature Relationships
Pairplots and boxplots were used to explore deeper relationships between variables.

### Observations:
- Smokers show extreme outliers in insurance charges  
- Southeast region has slightly higher premiums on average  
- BMI and age have a stronger combined effect for smokers  

---

### 4. Smoking vs Age Impact
Regression plots were used to analyze how charges change with age across smoking groups.

### Observations:
- Smokers show a sharp increase in charges with age  
- Non-smokers show a gradual increase in costs  
- Smoking significantly amplifies risk over time  

---

## 📌 Key Insights
- Smoking status is the strongest predictor of insurance charges  
- Age has a consistent positive correlation with premiums  
- Higher BMI (especially obesity) leads to increased charges  
- Region and number of children have a relatively minor impact  

---

## 💡 Business Impact
- Smoking-based risk pricing models should be prioritized  
- Preventive health programs could reduce long-term claims  
- BMI and age-based segmentation can improve premium accuracy  
- Insights can support development of a predictive pricing model  

---

## 🧠 Summary
This analysis shows that lifestyle factors—especially smoking—have a major influence on insurance costs. 
These findings provide a strong foundation for building predictive models and improving risk-based pricing strategies.

---

## 📊 Visual Insights

### Sex Distribution
![Sex](visuals/sex_countplot.png)

### Smoking Impact
![Smoker](visuals/smoker_countplot.png)

### Age vs Charges
![Age](visuals/age_vs_charges.png)

### BMI vs Charges
![BMI](visuals/bmi_vs_charges.png)

### Pairplot Analysis
![Pairplot](visuals/pairplot.png)
