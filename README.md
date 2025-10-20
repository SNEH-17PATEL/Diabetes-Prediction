# 🩺 Diabetes Prediction System

This project predicts **whether a person is diabetic or non-diabetic** using a Support Vector Machine (SVM) model.  
It includes data preprocessing, standardization, model training, evaluation, and a predictive system for new data points.

---

## 📊 Project Overview

The goal is to build a machine learning system that can classify individuals as diabetic or non-diabetic based on diagnostic measurements.  
The workflow includes:
- Loading and exploring the dataset  
- Data standardization (feature scaling)  
- Splitting data into training and testing sets  
- Training an SVM classifier  
- Evaluating the model with accuracy scores  
- Making predictions on new input data  

---

## 🧰 Tech Stack

- **Python 3**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Scikit-learn**  

---

## 📂 Dataset

- **File used:** `diabetes.csv`  
  The dataset includes the following columns:
  - `Pregnancies`: Number of pregnancies  
  - `Glucose`: Plasma glucose concentration  
  - `BloodPressure`: Diastolic blood pressure  
  - `SkinThickness`: Triceps skin fold thickness  
  - `Insulin`: 2-Hour serum insulin  
  - `BMI`: Body mass index  
  - `DiabetesPedigreeFunction`: Genetic factor  
  - `Age`: Age of the patient  
  - `Outcome`: 0 (Non-diabetic), 1 (Diabetic)  

📊 Dataset source: [Pima Indians Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## 🚀 Features

1. **Data Exploration & Visualization**  
   - Check for null values, statistical analysis, and distributions  

2. **Data Preprocessing**  
   - Standardization using `StandardScaler`  
   - Separating features (`X`) and target (`y`)  

3. **Model Training & Evaluation**  
   - SVM classifier with linear kernel  
   - Accuracy measurement on training and testing data  

4. **Predictive System**  
   - Input new data points for real-time predictions  

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/SNEH-17PATEL/Diabetes-Prediction.git
cd Diabetes-Prediction
```

### 2. Install Dependencies
```bash
pip install numpy pandas matplotlib scikit-learn
```

### 3. Add Dataset
Place the `diabetes.csv` file in the project directory.
