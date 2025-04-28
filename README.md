# 🎯 Student Performance Analysis with Explainable AI (XAI)

**Repository to analyze, visualize, explain and document factors affecting student performance using EDA, Explainable AI, and automated PDF report generation.**

---

## 📂 Table of Contents
- [General Information](#general-information)
- [Objective](#objective)
- [Dataset Information](#dataset-information)
- [Project Pipeline](#project-pipeline)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [How to Use This Repository](#how-to-use-this-repository)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

---

## 📖 General Information

This project performs a comprehensive **Exploratory Data Analysis (EDA)** combined with **Explainable AI (XAI)** using SHAP-based methods.  
In addition, a **dynamic PDF report** containing all plots, graphs, and insights is automatically generated at runtime.

---

## 🎯 Objective

- Understand the relationship between demographic factors and academic performance.
- Perform meaningful visualizations to detect trends and correlations.
- Explain model decisions and feature impacts using XAI (SHAP values).
- Generate a well-structured, ready-to-share PDF report automatically.

---

## 📊 Dataset Information

- **Dataset:** Students Performance in Exams
- **Source:** [Kaggle - SPSScientist](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Features:**
  - `gender`
  - `race/ethnicity`
  - `parental level of education`
  - `lunch`
  - `test preparation course`
  - `math score`
  - `reading score`
  - `writing score`

---

## 🔥 Project Pipeline

1. **Data Loading and Preview**
2. **Data Cleaning and Preprocessing**
   - Check for missing values
   - Correct data types
3. **Exploratory Data Analysis (EDA)**
   - Categorical feature analysis (Countplots)
   - Numerical feature analysis (Distribution plots)
   - Correlation matrix heatmap
4. **Explainable AI (XAI) Analysis**
   - Train a basic ML model (e.g., DecisionTreeRegressor)
   - Use **SHAP** (SHapley Additive exPlanations) for:
     - Feature importance
     - Per-instance prediction explanation
5. **Automated PDF Report Generation**
   - All charts and analysis compiled into a professional PDF.
   - Report filename is dynamically generated based on date and time.

---

## 📈 Conclusions

- Completion of test preparation courses positively correlates with better exam performance.
- Gender and parental education show patterns affecting student scores.
- SHAP-based Explainable AI reveals that:
  - Test preparation and parental education level are the most influential features in predicting performance.
- Automated reporting enables quick and standardized report creation for stakeholders.

---

## 🛠 Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- shap
- fpdf
- datetime

---

## 🚀 How to Use This Repository

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/student-performance-analysis.git
   cd student-performance-analysis
