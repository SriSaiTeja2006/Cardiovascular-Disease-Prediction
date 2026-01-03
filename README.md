# ❤️ Cardiovascular Disease Prediction – Machine Learning Project

This repository contains a complete **end-to-end Machine Learning project** for predicting the risk of cardiovascular (heart) disease using patient health data.  
The project includes **data preprocessing, exploratory data analysis (EDA), feature correlation analysis, model training and evaluation**, and provides access to a **deployed Streamlit web application**.

---

## 🌐 Live Deployed Application (Streamlit)

👉 **Streamlit App Link:**  
https://heart-disease-prediction-5fzje5pmv29jnkedafbsfr.streamlit.app/

The deployed application allows real-time prediction of cardiovascular disease risk using a professional medical-style dashboard.

---

## 📌 Project Objective

Cardiovascular disease (CVD) is one of the leading causes of death worldwide. Early detection can significantly reduce complications and mortality rates.

The objective of this project is to:
- Analyze cardiovascular health data
- Identify key risk factors
- Build and evaluate multiple machine learning models
- Select the best-performing model
- Deploy the model as a real-time web application

---

## 📊 Dataset Description

The dataset used in this project contains patient medical and lifestyle information related to cardiovascular health.

### Features:
- **Age** (years)
- **Gender** (male/female)
- **Height** (cm)
- **Weight** (kg)
- **Systolic Blood Pressure (ap_hi)**
- **Diastolic Blood Pressure (ap_lo)**
- **Cholesterol Level**
- **Glucose Level**
- **Smoking Habit**
- **Alcohol Consumption**
- **Physical Activity**
- **Target Variable:** `cardio`  
  - `1` → Presence of cardiovascular disease  
  - `0` → No cardiovascular disease  

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:
- Removal of unnecessary columns
- Handling of incorrect and missing values
- Encoding categorical variables
- Feature scaling using **StandardScaler**
- Splitting data into training and testing sets

---

## 📈 Exploratory Data Analysis (EDA)

EDA was performed to understand data distribution and relationships between features.

### Analysis included:
- Distribution plots for numerical features
- Count plots for categorical features
- Outlier detection
- Correlation analysis using a **heatmap**

### 🔗 Correlation Matrix Insights
The correlation matrix helped identify:
- Strong relationships between blood pressure and heart disease
- Impact of cholesterol and glucose levels
- Influence of lifestyle factors such as smoking and physical activity

---

## 🤖 Machine Learning Models Implemented

Multiple machine learning algorithms were trained and evaluated:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- **Support Vector Machine (SVM)** ✅  

---

## 📊 Model Performance Comparison

| Model | Accuracy |
|------|----------|
| Logistic Regression | ~72% |
| KNN | ~64% |
| Decision Tree | ~63% |
| Random Forest | ~71% |
| **Support Vector Machine (SVM)** | **~72.6%** |

### ✅ Best Model Selected
The **Support Vector Machine (SVM)** model was selected due to:
- Higher accuracy
- Better generalization capability
- Robust performance on unseen data

---

## 💾 Model Saving

The trained model and scaler were saved using `joblib` for deployment:

- `heart_disease_model.pkl`
- `scaler.pkl`

These files are used directly in the deployed Streamlit web application.

---

## 🌐 Deployment (Streamlit)

The trained model is deployed as an interactive **Streamlit web application**, allowing users to:

- Enter patient health parameters
- Automatically calculate BMI
- View cardiovascular disease risk prediction
- See estimated risk percentage
- Understand key factors influencing the prediction
- Interact with a professional medical-style dashboard

---

## 🧮 Additional Features in Deployment

- Automatic **BMI calculation**
- **Risk percentage estimation** (SVM-safe method)
- Feature-level **explainability**
- **Medical disclaimer** for ethical and responsible usage
- User-friendly **Yes/No inputs** for lifestyle factors

---

## 📂 Repository Purpose

This repository focuses on:
- Machine learning model development
- Data analysis and visualization
- Model evaluation results
- Output screenshots and notebooks

👉 The **deployment-ready code** is maintained separately for clarity and cleanliness.

---

## 🔗 Related Repository

🚀 **Deployment & Source Code Repository:**  
(Replace with your main repo link)
