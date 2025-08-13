# Credit Card Fraud Detection

A Machine Learning project to detect fraudulent credit card transactions.  
Built with **Python**, **scikit-learn**, and **Random Forest Classifier**.

---

##  Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
---

##  Overview
This project detects fraudulent credit card transactions using a **Random Forest Classifier**.  
The dataset is highly imbalanced, so techniques like **SMOTE** and **class weighting** are used to handle imbalance.  
The workflow includes:
- Data preprocessing & handling missing values
- Exploratory Data Analysis (EDA)
- Model training & evaluation

---

##  Features
- Clean and preprocess transaction data  
- Handle imbalanced datasets with **SMOTE** or **class weights**  
- Train a **Random Forest Classifier**  
- Evaluate model using Accuracy, Precision, Recall, F1-Score, and ROC-AUC  
- Save trained model for future predictions

 ## Data-Set
  - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download

---

##  Project Structure
- data/ # Dataset files
-  notebooks/ # Jupyter notebooks for EDA & experiments
- src/ # Preprocessing & model scripts
-  models/ # Saved trained models
-  results/ # Metrics and plots
- requirements.txt # Dependencies
-  README.md

##  Installation
Clone the repository:
```bash
git clone https://github.com/<your-username>/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
