# Bank_Customer_Churn_Prediction
# 📊 Bank Customer Churn Analysis

## 🔍 Overview
This project predicts **bank customer churn** using machine learning techniques.  
The goal is to:
- Identify and visualize the factors contributing to churn.  
- Build a predictive model that classifies customers likely to churn.  
- Provide churn probability scores to help customer service teams **target at-risk customers** effectively.  

---

## 📂 Dataset
**Filename:** `Churn_Modelling.csv`  
**Size:** 1,000 rows × 14 attributes  
Each row represents a customer with demographic and account-related features.  

**Example Features:**
- Geographic Location  
- Gender  
- Credit Card User  
- Balance  

---

## 🎯 Project Objective
- Identify and visualize factors that drive customer churn.  
- Build a prediction model to:  
  - Classify if a customer is likely to churn.  
  - Provide churn probability for targeted interventions.  

---

## 🏗 Project Structure
- **Jupyter Notebook:** `bank-customer-churn-prediction.ipynb`  
  - Data exploration & preprocessing  
  - Model training & evaluation  
  - Comparison of multiple ML models  
  - Final model selection & predictions  

---

## 🤖 Machine Learning Models
Explored different ML algorithms that provide **classification & probability outputs**.  

**Evaluation Metrics:**
- Accuracy  
- Precision  
- Recall  
- AUC-ROC  

---

## ✅ Results
- The final model **effectively predicts customer churn**.  
- Probability-based predictions allow **customer service teams to focus on high-risk customers**.  
- Insights into key factors driving churn enable **data-driven business decisions**.  

---

## 🚀 How to Run the Project
1. Clone this repository.  
2. Place `Churn_Modelling.csv` in the project directory.  
3. Open `bank-customer-churn-prediction.ipynb` in Jupyter Notebook.  
4. Run all cells to perform the analysis and view results.  

---

## 📦 Requirements
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
