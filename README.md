# 🏦 Credit Scoring Model — German Credit Data  
**CodeAlpha Virtual Internship | Task 1**

---

## 📘 Project Overview
The **Credit Scoring Model** predicts whether a loan applicant has *Good Credit* or *Bad Credit* using the **German Credit Data with Risk** dataset from Kaggle.  
This project demonstrates the use of **Machine Learning in finance** for automating credit evaluation based on attributes such as age, job, housing, savings accounts, and credit amount.

It includes a complete ML pipeline for:
- Data preprocessing and encoding  
- Feature scaling with `StandardScaler`  
- Training multiple classification models  
- Model evaluation using accuracy and ROC–AUC  
- Saving models for reuse (no retraining required)  
- Predicting new applicants using trained models  

---

## 🚀 Features
- 🧩 Automatic data preprocessing (fills missing values, encodes categorical features)
- ⚙️ Trains and saves multiple models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
- 💾 Automatically loads existing `.pkl` models on subsequent runs  
- 📊 Evaluates model performance using:
  - Accuracy  
  - Classification Report  
  - ROC–AUC Score  
  - ROC Curves  
- 🤖 Predicts credit risk for new applicants using a simple Python dictionary input  
- 🔁 Reusable ML pipeline — models do not need retraining every time  

---

## 📊 Dataset Details
- **Dataset Name:** German Credit Data with Risk  
- **Source:** [Kaggle – German Credit Data with Risk](https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk)  
- **Target Column:** `Risk` → *Good* / *Bad*  
- **Attributes:** Age, Sex, Job, Housing, Saving accounts, Checking account, Credit amount, Duration, Purpose  

---

## 📁 Folder Structure
Credit_Scoring_Model/
│
├── data/
│ └── german_credit_data.csv
│
├── Credit_Scoring.ipynb
├── model_Logistic_Regression.pkl
├── model_Decision_Tree.pkl
├── model_Random_Forest.pkl
├── scaler.pkl
├── requirements.txt
├── .gitignore
└── README.md


---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<PrajwalN2305>/Credit-Scoring-Model.git
cd Credit-Scoring-Model
```
### 2 Create a Virtual Environment (Recommended)
```bash
python -m venv venv
venv\Scripts\activate
```
### 3 Install Required Packages
```bash
pip install -r requirements.txt

```
### 4 Run the Jupyter Notebook
```bash
jupyter notebook Credit_Scoring.ipynb

```
### 5 Requirements
```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib

