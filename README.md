# 🏥 MedPredict AI

### Healthcare Intelligence & Clinical Decision-Support Platform

MedPredict AI is an interactive healthcare analytics and AI platform designed to demonstrate how machine learning, business intelligence, clinical risk analysis, and data engineering workflows can be integrated into a unified healthcare application.

The platform combines patient analytics, readmission risk prediction, ML model evaluation, clinical workflow demonstrations, SQL analytics, anomaly detection, and healthcare BI dashboards in a single interface.

## 🚀 Live Demo

**Live Application:**  
https://ayushi18s.github.io/MedPredict-AI/

---

## ✨ Key Features

### 📊 Analytics
- Live healthcare analytics dashboard
- Patient registry
- Clinical insights
- KPI monitoring
- Readmission analysis
- Department-level analytics

### 🧠 Artificial Intelligence
- Patient readmission risk prediction
- Random Forest classification model
- Logistic Regression baseline
- Gradient Boosting comparison
- Feature importance analysis
- Model performance evaluation
- ML model laboratory with confusion matrix and evaluation metrics

### 🏥 Clinical Services
- AI-assisted risk report generation
- Doctor/specialist recommendation workflow
- Appointment priority management
- Treatment category advisor
- Clinical decision-support demonstrations

### 📈 Business Intelligence
- Hospital KPI dashboard
- Department scorecards
- Readmission trends
- Cost-efficiency analysis
- Bed occupancy analytics
- AI impact metrics

### 🗄️ Data & SQL Analytics
- SQL analytics workbench
- Patient-level analytical queries
- Diagnosis analysis
- Readmission analysis
- Medication-load analysis
- Department risk ranking
- Monthly trend analysis

### 🚨 Anomaly Detection
- Isolation Forest-based anomaly detection
- Z-score deviation analysis
- Patient risk/anomaly flags
- Medication-load anomaly detection
- Clinical pattern monitoring

---

## 🤖 Machine Learning

The primary predictive model is a **Random Forest classifier** designed to demonstrate patient readmission-risk prediction.

### Model Comparison

| Model | Accuracy | Precision | Recall | F1 Score | AUC |
|---|---:|---:|---:|---:|---:|
| Random Forest | 86% | 84% | 82% | 83% | 0.91 |
| Logistic Regression | 79% | 76% | 74% | 75% | 0.83 |
| Gradient Boosting | 83% | 81% | 79% | 80% | 0.88 |

### Random Forest Configuration

- Number of trees: 200
- Maximum depth: 12
- Minimum samples split: 5
- Minimum samples leaf: 2
- Class weight: Balanced
- Random state: 42
- Cross-validation: 5-fold
- Hyperparameter optimization: Grid Search

### Important Features

The platform highlights features such as:

- Blood sugar control
- Total medications prescribed
- Admission type
- Days spent in hospital
- Patient age group
- Primary diagnosis type

---

## 🔄 ML Pipeline

```text
UCI Diabetes Dataset
        ↓
Exploratory Data Analysis
        ↓
Data Cleaning
        ↓
Missing-Value Handling
        ↓
Categorical Encoding
        ↓
SMOTE
        ↓
Train/Test Split
        ↓
Grid Search + Cross Validation
        ↓
Random Forest Model
        ↓
Risk Prediction
        ↓
Clinical Analytics & Visualization
