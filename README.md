# 📊 Customer Churn Prediction

## 📌 Overview
This project predicts **customer churn** — whether a customer is likely to discontinue a service — using machine learning.  
By analyzing demographic details, contract information, and service usage, the model helps businesses identify at-risk customers and take proactive retention measures.

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / Google Colab  

## ✨ Features
- Cleaned and preprocessed raw customer dataset  
- Performed **Exploratory Data Analysis (EDA)** with visualizations to uncover churn patterns  
- Applied **feature engineering** to improve model performance  
- Built and compared multiple ML models: Logistic Regression, Random Forest  
- Evaluated models with **Accuracy, Precision, Recall, and ROC-AUC**  

## 📊 Results
- Final model: **Random Forest Classifier**  
- Achieved:  
  - **Accuracy:** 78%  
  - **ROC-AUC:** 0.81  
- Example Prediction:  
Input: Customer demographic & usage data
Prediction: No Churn
Probability: [No Churn: 0.78, Churn: 0.22]
- Identified **key churn-driving features**: contract type, tenure, monthly charges  

## 📂 Project Structure
Customer-Churn-Prediction/
│── customer_churn.ipynb # Main notebook
│── requirements.txt # Dependencies
│── README.md # Documentation
└── dataset.csv # Dataset (Telco Customer Churn from Kaggle)

## 📑 Dataset
- Source: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- Contains customer demographic info, contract details, services used, and churn status  

## 🚀 Future Improvements
- Add advanced models (XGBoost, LightGBM, Neural Networks)  
- Perform hyperparameter tuning for higher accuracy  
- Deploy the model as a **Streamlit/Flask web app** for interactive predictions  

## 👨‍💻 Author
**Rohan Roy**  
- [GitHub](https://github.com/Yash-Rohan)  
- [LinkedIn](https://www.linkedin.com/in/rohan-roy-5205861b5/)  
