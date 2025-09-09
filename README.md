# British Airways Data Science Simulation – Task 2 ✈️  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-008080)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview  

This repository contains my work on **Task 2 of the British Airways Data Science Virtual Internship (Forage)**.  

The goal was to **predict customer buying behaviour** using machine learning and identify the **factors that influence whether a customer makes a purchase** before their holiday.  

This task simulates how **data science can help airlines optimize marketing strategies, improve customer acquisition, and increase conversion rates**.  

---

## 🎯 Objectives  

- Prepare and preprocess the customer dataset.  
- Perform **exploratory data analysis (EDA)** to understand key features.  
- Build a **predictive model** to classify buying behaviour.  
- Evaluate model performance using cross-validation and F1 score.  
- Present findings with insights and recommendations.  

---

## 🛠 Tools & Technologies  

- **Python** (Pandas, NumPy, Scikit-learn)  
- **Visualization**: Matplotlib, Seaborn  
- **Modeling**: Logistic Regression, Random Forest, Cross-validation  
- **Notebook Environment**: Jupyter Notebook  

---

## 📊 Approach  

1. **Data Preparation**  
   - Cleaned and preprocessed raw dataset.  
   - Handled missing values, categorical encoding, and feature scaling.  

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed relationships between features and customer purchase decision.  
   - Visualized key trends influencing buying behaviour.  

3. **Model Training**  
   - Trained classification models to predict customer purchase.  
   - Used **k-fold cross-validation** for robust evaluation.  

4. **Evaluation**  
   - Measured model performance using **accuracy, precision, recall, and F1-score**.  
   - Example result:  
     ```
     Cross-Validated F1 Scores: [0.5006, 0.5052, 0.5027, 0.5024, 0.4928]
     Mean F1 Score: 0.50
     Standard Deviation: 0.00
     ```
   - Model was **stable but underperforming** → highlighted need for feature engineering & advanced models.  

---

## 📈 Results & Insights  

- Baseline model achieved an **F1 score of ~0.50**, showing balanced but limited predictive power.  
- Identified potential drivers of customer purchase such as **demographics, booking patterns, and travel preferences**.  
- Recommendations:  
  - Apply feature engineering to extract stronger signals.  
  - Try ensemble models (Random Forest, XGBoost) for better performance.  
  - Address class imbalance to improve recall on minority class.  

---

## 📂 Repository Structure  

