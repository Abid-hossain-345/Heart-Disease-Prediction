# Heart-Disease-Prediction

This project predicts the likelihood of heart disease in patients based on their health parameters using the **K-Nearest Neighbors (KNN)** algorithm.  
It is implemented in Python and deployed as an interactive web app on **Hugging Face Spaces**.

## 🚀 Live Demo
Try the app here: [Heart Disease Prediction on Hugging Face](https://huggingface.co/spaces/Abhi131002/knn-heart-disease)

---

## 📌 Project Overview
Heart disease is one of the leading causes of death globally. Early prediction can help in timely diagnosis and preventive care.  
This machine learning model uses patient data (e.g., age, cholesterol, blood pressure, heart rate) to predict the probability of heart disease.

### **Algorithm Used**
- **K-Nearest Neighbors (KNN)**: A simple, non-parametric, and effective classification algorithm that works by finding the closest data points (neighbors) and making predictions based on their classes.

---

## 📂 Dataset
The dataset used in this project contains medical attributes like:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- Oldpeak (ST depression)
- Slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia

**Target variable:**
- `0` → No heart disease
- `1` → Heart disease present

📊 Model Performance

Accuracy: ~85-97% (depending on dataset split and preprocessing)

Evaluation: Cross-validation (cv=10) for reliable results

🛠 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn (data visualization)

Hugging Face Spaces (deployment)

Jupyter Notebook
