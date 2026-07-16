# Diabetes Prediction

Predicting diabetes risk from diagnostic health measurements using a Support Vector Machine (SVM) classifier — built as part of the AI/ML Internship at Naviotech Solution Pvt. Ltd. (June 2026).

## 📌 Overview

This project uses the PIMA Indians Diabetes dataset to predict whether a patient is diabetic, based on 8 diagnostic measurements such as glucose level, BMI, and blood pressure.

## 📊 Dataset

- **Source:** PIMA Indians Diabetes Dataset
- **Size:** 768 rows, 8 features
- **Target:** `Outcome` (1 = Diabetic, 0 = Non-Diabetic) — ~35% diabetic

## 🛠️ Approach

1. **Data Preprocessing** — separated features and target, applied StandardScaler for feature scaling
2. **Train-Test Split** — 80% training (614 samples), 20% testing (154 samples), stratified
3. **Model** — Support Vector Machine (SVM) with a linear kernel
4. **Evaluation** — measured accuracy on both training and test sets to check generalization
5. **Predictive System** — built a working function to classify new patient input

## 📈 Results

| Metric | Score |
|---|---|
| Training Accuracy | 78.66% |
| Test Accuracy | 77.27% |

The small gap between training and test accuracy shows the model generalizes well without overfitting.

## 📁 Repository Contents

| File | Description |
|---|---|
| `Diabetes_Prediction.ipynb` | Full Jupyter notebook — preprocessing, training, evaluation |
| `diabetes.csv` | Dataset used for training and evaluation |
| `Diabetes_Prediction_Report.docx` | Detailed project report |
| `Diabetes_Prediction.pptx` | Presentation summary (10 slides) |

## 🧰 Tech Stack

Python · pandas · scikit-learn · numpy

## 🚀 Future Scope

- Try other SVM kernels (RBF, polynomial) for comparison
- Test ensemble models like Random Forest
- Deploy as a simple health-screening web app

## 👤 Author

**Arya Anshuman Panda** — B.Tech CSE (Data Science), Gandhi Engineering College, Bhubaneswar
AI/ML Intern, Naviotech Solution Pvt. Ltd.
