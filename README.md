# 🔋 Lithium Battery EIS Classification and Regression (2024)

## 📌 Project Overview
This project applies **machine learning models** to classify and predict key electrochemical properties of **Lithium-ion batteries (Li-ion) using Electrochemical Impedance Spectroscopy (EIS) data**. 

The goal is to:
1. **Classify battery health states** based on EIS measurements 
2. **Predict the Remaining Useful Lifecycle (RUL) of lithium-ion batteries

## 📊 Dataset
- The dataset consists of **EIS measurements** collected from lithium-ion batteries under different conditions.
- **Key Features:**
  - Impedance values at different frequencies.
  - Real and imaginary parts of impedance.
  - Battery state-of-health (SoH) indicators.
  - **Cycle life data for RUL estimation.**
  - Cleaning and presprocessing data using pandas

## 🔬 Machine Learning Approach
This project includes **classification and regression** tasks using different models:

### **1️⃣ Classification Task**
- **Goal:** Categorize batteries into different health states.
- **Model Used:**  
  ✅ **Support Vector Machine (SVM)** – Achieved **100% accuracy** in classifying battery health states.

### **2️⃣ Regression Task**
- **Goal:** Predict the **Remaining Useful Lifecycle (RUL)** of lithium-ion batteries.  
- **Model Used:**  
  ✅ **Lasso Regression** – Achieved **R² > 90%** for predicting battery RUL.  
  ✅ Also used **Lasso for feature selection**, identifying the most relevant EIS-based predictors of **battery degradation trends**.

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/adilamin89/Lithium_Battery_EIS_Classification_and_Regression_2024.git
cd Lithium_Battery_EIS_Classification_and_Regression_2024


