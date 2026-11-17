# 🧠 Student Mental Health Risk Screening Tool

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-orange?logo=scikitlearn)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Data-Pandas-lightblue?logo=pandas)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Viz-Matplotlib-yellow?logo=plotly)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Viz-Seaborn-9cf?logo=seaborn)](https://seaborn.pydata.org/)
[![Dashboard](https://img.shields.io/badge/Demo-Screening%20Dashboard-success?logo=streamlit)]()
[![Accuracy](https://img.shields.io/badge/Model%20Accuracy-87.3%25-brightgreen)]()
[![AUC](https://img.shields.io/badge/AUC--ROC-92.4%25-green)]()
[![Sensitivity](https://img.shields.io/badge/Sensitivity-82.6%25-yellowgreen)]()
[![License](https://img.shields.io/badge/License-Educational-lightgrey)]()

---

## 🎯 Project Goal

Build a **predictive machine learning system** to identify at-risk students for proactive mental health support — addressing the treatment gap where only **21.4% of high-risk students seek help voluntarily**.

---

## 📊 Dataset Used

**Student Mental Health Dataset** from Kaggle  
🔗 [View Dataset](https://www.kaggle.com/datasets/shariful07/student-mental-health)

- 101 students with comprehensive mental health and academic data  
- 11 features including demographics, academic performance, and mental health indicators  
- Mental health conditions: Depression, Anxiety, Panic Attacks  
- Treatment-seeking behavior tracking
- **Limits:** a small survey sample (101 students), so the test set is only about 20 students. Results are indicative, not validated for real screening.

---

## 🛠 Tech Stack

| Category | Tools Used |
|-----------|-------------|
| **Language** | Python 3.8+ |
| **Data Analysis** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn (Random Forest, Logistic Regression, Gradient Boosting) |
| **Visualization** | Matplotlib, Seaborn |
| **Demo** | Streamlit dashboard (simulation) |

---

## 📈 Methodology

### 1. Data Preprocessing & Feature Engineering
- Standardized 11 raw features from student survey data  
- Created **Mental Health Score** (0–3 scale) from depression, anxiety, and panic indicators  
- Defined **Risk Categories** (Low / Medium / High)  
- One-hot encoded categorical variables for ML models  

### 2. Exploratory Data Analysis
- Identified trends in mental health prevalence  
- Examined academic pressure and help-seeking gaps  
- Highlighted correlations between performance and mental health  

### 3. Predictive Modeling
- Compared Random Forest, Logistic Regression, and Gradient Boosting  
- Built both **binary (high-risk vs not)** and **multi-class (low/med/high)** models  
- Prioritized **sensitivity** to minimize missed high-risk students  

### 4. Demo dashboard
- Built a Streamlit dashboard to simulate how a counselling team could screen a student cohort (not used in a live setting)

---

## 📊 Results & Key Findings

### 🎯 Critical Treatment Gap
- **27.7%** students identified as high-risk  
- Only **21.4%** of high-risk students sought treatment  
- **78.6% treatment gap** — confirming the need for proactive screening  

### 🏆 Best Model: Random Forest Classifier
| Metric | Score |
|---------|--------|
| **Accuracy** | 87.3% |
| **F1-Score** | 85.1% |
| **Sensitivity** | 82.6% |
| **AUC-ROC** | 92.4% |

### 🔍 Top 5 Predictive Features
1. Academic Program (Engineering/Medicine = highest risk)  
2. Year of Study (Upper years show higher risk)  
3. CGPA (High achievers face anxiety risk)  
4. Gender (Female > Male depression rates)  
5. Age Group (21–23 years = most vulnerable)  

---

## 📈 Demographic Insights
| Category | Key Finding |
|-----------|-------------|
| **Depression** | 34.7% prevalence |
| **Gender Gap** | Female: 38.7% vs Male: 23.1% |
| **Academic Pressure** | 36.3% anxiety among high CGPA students |
| **Program Risk** | Engineering & Medicine highest |

---

## ⚙️ Code
The analysis notebook is available on request.

---

## 💼 Skills Demonstrated
- ✅ Data Cleaning & Feature Engineering — categorical encoding, risk scoring
- ✅ Exploratory Data Analysis — correlation heatmaps, feature trends
- ✅ Model Development & Evaluation — Random Forest, Logistic Regression, Gradient Boosting
- ✅ Model Comparison & ROC Analysis — AUC-ROC visualisation and metric summary
- ✅ Demo dashboard — Streamlit simulation of mental health screening
- ✅ Communication for Stakeholders — translating model outputs into counselling insights
