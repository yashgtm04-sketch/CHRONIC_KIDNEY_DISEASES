## Early Detection of Chronic Kidney Disease Using Machine Learning
## Project Overview
This project focuses on the early detection of Chronic Kidney Disease (CKD) using machine learning techniques on real-world clinical data. The goal is to build reliable classification models that assist in early diagnosis and risk assessment.

## Dataset
Records: 400 Type: Medical / clinical dataset Target Variable: CKD Classification (CKD / Not CKD)

## Key Features:
• Blood Urea • Serum Creatinine • Hemoglobin • Blood Pressure • Age and other clinical indicators

## Exploratory Data Analysis (EDA)
Analyzed class distribution to check data balance Examined missing values and data quality issues Used histograms to study distributions of key numerical features Applied boxplots to identify extreme clinical values Used a correlation heatmap to understand feature relationships

## Key Insights:
• Several clinical features showed right-skewed distributions • Extreme values present in blood urea and serum creatinine • Data characteristics justified robust preprocessing before modeling

## Data Preprocessing
Performed data cleaning and encoding of 11 categorical features Detected outliers using IQR / box-plot methods Applied outlier capping to control extreme values Imputed missing values using mean and mode Applied feature scaling where required

## Machine Learning Models
Logistic Regression – baseline classification model Random Forest Classifier – non-linear, tree-based model

Models were trained using an 80/20 train–test split and compared using cross-validation to ensure generalization.

## Results & Findings
Achieved stable predictive performance (accuracy ≈ 0.96–0.98) Evaluated models using confusion matrices and classification reports Random Forest demonstrated strong performance in capturing non-linear clinical patterns Results support the feasibility of early CKD detection using ML

## Tools Used
Python Pandas, NumPy Matplotlib, Seaborn Scikit-learn Jupyter Notebook
