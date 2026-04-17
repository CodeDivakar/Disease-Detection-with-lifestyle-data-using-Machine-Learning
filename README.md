# 🏥 AI Health Risk Prediction System

## 📌 Project Overview

This project is an end-to-end Machine Learning system that predicts the risk of multiple diseases based on user lifestyle and health parameters.

The system currently predicts:

* Diabetes Risk
* Heart Disease Risk

It also provides:

* Risk levels (Low / Medium / High)
* Health score
* Basic lifestyle recommendations

---

## 🎯 Objective

The goal of this project is to build a real-world healthcare support system that helps users understand their potential health risks early and take preventive actions.

---

## 🧠 Key Features

* Multi-disease prediction system
* Uses separate ML models for each disease
* Real-time predictions using Streamlit UI
* Lifestyle-based recommendations
* Health score calculation
* Clean and user-friendly interface

---

## 🏗️ Project Architecture

User Input → Data Processing → ML Models → Risk Prediction → Recommendations → UI Display

---

## 📊 Datasets Used

### 1. Diabetes Dataset

* Source: UCI Machine Learning Repository
* Rows: 768
* Target: Outcome (0 = No Diabetes, 1 = Diabetes)

### 2. Heart Disease Dataset

* Source: UCI / Cleveland Dataset
* Rows: 303
* Target: target (0 = No Disease, 1 = Disease)

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Streamlit
* Joblib

---

## 🤖 Machine Learning Models

* Random Forest Classifier (for both diseases)

---

## 📈 Model Performance

| Model          | Accuracy | Recall |
| -------------- | -------- | ------ |
| Diabetes Model | ~75%     | ~82%   |
| Heart Model    | ~82%     | High   |

> Note: Recall is prioritized since missing a disease case is more critical than false positives.

---

## 🧹 Data Preprocessing

* Handled missing values (replaced invalid zeros with mean)
* Feature scaling applied
* Feature selection based on dataset structure

---

## 🚀 How to Run the Project

### 1. Clone Repository

```
git clone https://github.com/your-username/health-risk-project.git
cd health-risk-project
```

### 2. Install Requirements

```
pip install -r requirements.txt
```

### 3. Train Models

```
python train_models.py
```

### 4. Run Application

```
streamlit run app.py
```

---

## 🖥️ Application Workflow

1. User enters health details (age, BMI, glucose, etc.)
2. Data is processed and formatted
3. Input is passed to multiple ML models
4. Each model predicts disease risk
5. Results are combined into a final report
6. Suggestions and health score are displayed

---

## ⚠️ Disclaimer

This project is for educational purposes only and should not be used as a medical diagnosis tool.

---

## 🔮 Future Improvements

* Add more diseases (hypertension, obesity, etc.)
* Integrate SHAP explainability
* Improve UI/UX
* Use real-time health data APIs
* Deploy as a web/mobile app

---

## 🧑‍💻 Author

Divakar S

---

## ⭐ If you like this project

Give it a star on GitHub ⭐
