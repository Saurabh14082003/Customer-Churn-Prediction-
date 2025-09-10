# Autoencoder for Customer Churn Prediction

This project demonstrates how to use **Autoencoders** for **customer churn analysis**. By leveraging unsupervised learning, the autoencoder learns normal customer behavior patterns and identifies deviations that could indicate churn risk.  

## 📌 Project Overview
- Applied an **Autoencoder neural network** to customer churn data.  
- Goal: Detect potential churners based on anomalies in feature reconstruction.  
- The model learns compressed representations of customer behavior and highlights customers with higher reconstruction error as "at risk".

## ⚙️ Features
- Data preprocessing & cleaning (handling categorical and numerical variables).  
- Autoencoder architecture built with **Keras/TensorFlow**.  
- Training to minimize reconstruction loss (MSE).  
- Evaluation using reconstruction error distribution.  
- Visualization of churn vs. non-churn error separation.  

## 🛠️ Tech Stack
- **Python 3.10+**  
- **Libraries**: pandas, numpy, scikit-learn, TensorFlow/Keras, matplotlib, seaborn  

## 🚀 Workflow
1. **Data Loading** – Load the churn dataset and perform exploratory data analysis (EDA).  
2. **Preprocessing** – Encode categorical variables, normalize numerical features, and split data.  
3. **Autoencoder Model** – Encoder compresses input features, decoder reconstructs them, reconstruction error used for anomaly detection.  
4. **Evaluation** – Plot reconstruction error distribution, identify high-error customers, compare against actual churn labels.  

## 📊 Results
- Customers with higher reconstruction error values show a strong correlation with actual churners.  
- Autoencoders provide a powerful unsupervised approach for churn prediction when labels are limited.  

## 📂 Repository Structure
📦 Autoencoder-for-Customer-Churn  
 ┣ 📜 Autoencoder for Customer Churn.ipynb  
 ┣ 📜 README.md  
 ┗ 📂 data (optional, not uploaded here)  

## 🧩 Future Improvements
- Hyperparameter tuning of the Autoencoder architecture.  
- Compare performance with supervised models (Logistic Regression, Random Forest, XGBoost).  
- Deploy model as an API for real-time churn prediction.  

## ✨ Author
Developed by **Saurabh Saini** 👨‍💻
