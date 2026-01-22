# Cloud-Based Drug Data Analytics using Snowflake

This project implements a **Machine Learning model using Naive Bayes Classifier** to predict the **type of drug** based on patient health attributes.  
The project covers the **complete ML pipeline** including **cloud data storage in Snowflake, SQL querying, data preprocessing, visualization, model training, evaluation, and prediction**, making it ideal for **placements, interviews, and academic submissions**.

---

## Project Overview

- **Algorithm Used:** Naive Bayes Classifier  
- **Domain:** Machine Learning / Data Science / Healthcare Analytics  
- **Programming Language:** Python  
- **Cloud Platform:** Snowflake  
- **Notebook Platform:** Google Colab  
- **Version Control:** Git & GitHub  

---

## Dataset Information

- **Dataset Name:** Drug200 Dataset  
- **Total Samples:** 200  
- **Number of Features:** 5  
- **Target Classes:** Multiple Drug Categories  

---

## Features

- Age  
- Sex  
- Blood Pressure  
- Cholesterol  
- Sodium-to-Potassium Ratio  
- Drug Type (Target Label)  

---

## Technologies Used

- Snowflake (Cloud Data Warehouse)  
- SQL  
- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Google Colab  
- GitHub  

---

## Project Workflow

1. Upload dataset to **Snowflake**
2. Store and manage healthcare drug data in cloud tables  
3. Execute SQL queries to retrieve patient data  
4. Load dataset into Python using Pandas  
5. Encode categorical features  
6. Train **Naive Bayes Classifier**  
7. Evaluate model performance  
8. Generate predictions and visualize results  

---

## Machine Learning Algorithm — Naive Bayes

Naive Bayes is a **probabilistic classification algorithm** based on **Bayes’ Theorem**.  
It assumes independence between features and is known for being **fast, efficient, and accurate**, especially for structured datasets.

### Advantages
- Fast training and prediction  
- Works well with categorical and numerical data  
- Lightweight and memory efficient  
- Suitable for medical and healthcare analytics  

---

## Data Visualization & Model Insights

### 🔹 Snowflake Drug Table Preview
<img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/4a7066c8-c2d9-4b2b-bad2-988dff5287eb" />

The dataset is stored in **Snowflake Cloud**, containing patient attributes such as age, blood pressure, cholesterol levels, and sodium-to-potassium ratio.  
This ensures **secure, scalable, and cloud-ready healthcare analytics**.

---

### 🔹 Confusion Matrix (Naive Bayes)

<img width="501" height="393" alt="image" src="https://github.com/user-attachments/assets/b693db76-9e9e-4b38-a668-8e123548333a" />

The confusion matrix visualizes the model’s prediction accuracy across all drug categories.
### Insights:
- Most predictions lie along the **diagonal**, indicating **high accuracy**
- Very few misclassifications occurred  
- Strong performance across all drug classes  
- Confirms the reliability of **Naive Bayes** for drug prediction  

---

### 🔹 Model Accuracy
- The model correctly predicts **90% of drug types**
  
### 📌 Interpretation:
- Demonstrates strong predictive performance  
- Suitable for healthcare decision-support systems  

