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

* Healthcare analytics dashboard
* Patient registry
* Clinical insights
* KPI monitoring
* Readmission analysis
* Department-level analytics

### 🧠 Artificial Intelligence

* Patient readmission risk prediction
* Random Forest classification
* Logistic Regression baseline
* Gradient Boosting comparison
* Feature importance analysis
* Model performance evaluation
* Confusion matrix and evaluation metrics

### 🏥 Clinical Services

* AI-assisted risk report generation
* Doctor/specialist recommendation workflow
* Appointment priority management
* Treatment category advisor
* Clinical decision-support demonstrations

### 📈 Business Intelligence

* Hospital KPI dashboard
* Department scorecards
* Readmission trends
* Cost-efficiency analysis
* Bed occupancy analytics
* AI impact metrics

### 🗄️ Data & SQL Analytics

* SQL analytics workbench
* Patient-level analytical queries
* Diagnosis analysis
* Readmission analysis
* Medication-load analysis
* Department risk ranking
* Monthly trend analysis

### 🚨 Anomaly Detection

* Isolation Forest-based anomaly detection
* Z-score deviation analysis
* Patient risk/anomaly flags
* Medication-load anomaly detection
* Clinical pattern monitoring

---

## 🤖 Machine Learning

The primary predictive model is a **Random Forest classifier** designed to demonstrate patient readmission-risk prediction.

### Model Comparison

| Model               | Accuracy | Precision | Recall | F1 Score |  AUC |
| ------------------- | -------: | --------: | -----: | -------: | ---: |
| Random Forest       |      86% |       84% |    82% |      83% | 0.91 |
| Logistic Regression |      79% |       76% |    74% |      75% | 0.83 |
| Gradient Boosting   |      83% |       81% |    79% |      80% | 0.88 |

### Random Forest Configuration

* Number of trees: 200
* Maximum depth: 12
* Minimum samples split: 5
* Minimum samples leaf: 2
* Class weight: Balanced
* Random state: 42
* Cross-validation: 5-fold
* Hyperparameter optimization: Grid Search

### Important Features

* Blood sugar control
* Total medications prescribed
* Admission type
* Days spent in hospital
* Patient age group
* Primary diagnosis type

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
```

---

## 🧰 Technology Stack

### Programming & Data

* Python
* SQL
* Pandas
* NumPy
* Scikit-learn

### Machine Learning

* Random Forest
* Logistic Regression
* Gradient Boosting
* SMOTE
* Grid Search
* Isolation Forest
* Statistical anomaly detection

### Analytics & Visualization

* Power BI
* DAX
* KPI reporting
* Interactive dashboards
* Data visualization

### Web Application

* HTML
* CSS
* JavaScript
* Interactive web interface

### Data Engineering Concepts

* ETL / data preprocessing
* Data cleaning
* Feature engineering
* Analytical SQL
* Data validation
* Model evaluation

---

## 🏥 Clinical Workflow Demonstrations

### Risk Report Generator

Generates structured risk-report views based on patient information and predicted risk.

### Doctor Recommender

Demonstrates rule-based routing of patients toward relevant medical departments based on diagnosis and severity-related inputs.

### Appointment Priority

Demonstrates risk-based patient queue prioritization.

### Treatment Advisor

Provides treatment-category suggestions based on patient characteristics and risk factors.

These features demonstrate healthcare decision-support concepts and are not intended to replace qualified healthcare professionals.

---

## 🗄️ SQL Analytics

The platform includes an interactive SQL analytics workbench with example healthcare queries covering:

* Readmission rates by age group
* Top diagnoses by readmission
* Emergency patient analysis
* Department risk ranking
* Medication-load analysis
* Monthly readmission trends
* Discharge outcomes

Example analytical query:

```sql
SELECT 
    age_group,
    COUNT(*) AS total_patients,
    SUM(readmitted_flag) AS total_readmitted,
    ROUND(AVG(readmitted_flag) * 100, 1) AS readmission_rate_pct
FROM patients
GROUP BY age_group
ORDER BY age_group;
```

---

## 🚨 Anomaly Detection

The platform demonstrates anomaly detection using:

* Isolation Forest
* Z-score deviation analysis
* Medication-load monitoring
* Unusual HbA1c patterns
* Recurring emergency admission patterns

These workflows are presented as demonstrations of how automated healthcare monitoring could be implemented.

---

## 📊 Healthcare BI Dashboard

The BI module demonstrates hospital analytics including:

* Department scorecards
* Patient volumes
* Readmission rates
* Average length of stay
* Cost-efficiency indicators
* Bed occupancy
* Emergency wait-time analytics
* Patient satisfaction indicators
* AI impact metrics

---

## ⚠️ Data & Clinical Disclaimer

**MedPredict AI is an educational and portfolio demonstration project.**

The machine-learning component is based on the publicly available UCI Diabetes dataset.

Hospital operational dashboards, KPI values, patient workflow examples, queue information, alerts, and other operational interface elements may contain **simulated/demo data** created to demonstrate how a healthcare intelligence platform could operate.

The platform has **not been clinically validated** and should not be used for actual diagnosis, treatment, patient triage, or medical decision-making.

Treatment and clinical workflow features demonstrate decision-support concepts and are not medical advice.

---

## 🎯 Project Objectives

MedPredict AI demonstrates the integration of:

* Machine learning
* Predictive analytics
* Healthcare BI
* SQL analytics
* Data preprocessing
* Feature engineering
* Anomaly detection
* Clinical workflow automation
* Decision-support interfaces
* Interactive dashboards

The objective is to demonstrate an end-to-end healthcare analytics and AI platform using a unified application interface.

---

## 📂 Platform Modules

```text
MedPredict AI
│
├── Analytics
│   ├── Dashboard
│   ├── Patient Registry
│   └── Clinical Insights
│
├── Artificial Intelligence
│   ├── Risk Predictor
│   └── ML Model Lab
│
├── Clinical Services
│   ├── Risk Report Generator
│   ├── Doctor Recommender
│   ├── Appointment Priority
│   ├── BI Health Dashboard
│   └── Treatment Advisor
│
└── Data Engineering
    ├── SQL Workbench
    └── Anomaly Alerts
```

---

## 👩‍💻 Author

**Ayushi**

B.Tech — Computer Science & Engineering (Data Science)

**GitHub:**
https://github.com/Ayushi18s

**LinkedIn:**
https://www.linkedin.com/in/ayushi-00024a311/

---

## ⭐ Project Status

**Status:** Completed Portfolio Project

**Version:** 4.0.0

The project is maintained for portfolio and demonstration purposes.
