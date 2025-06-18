# 📊 HR Attrition Analysis

## 🧠 Overview
This project analyzes employee attrition trends using the IBM HR Analytics dataset. It combines SQL and Python to extract insights into employee performance, tenure, role stability, and demographic attrition patterns.

**Industry:** Human Resources  
**Objective:** Identify key attrition drivers and present actionable insights to reduce turnover.

---

## 📁 Dataset

**Source:** [Kaggle – IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

The dataset includes employee-level data such as age, department, job role, attrition status, years at company, salary, and more.

---

## ⚙️ Technologies Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **SQL** (PostgreSQL or SQLite)
- **Jupyter Notebook**
- **CSV Data Loading & Cleaning**
- **Relational Database Storage**
- **Data Visualization**

---

## 📌 Project Tasks

- ✅ Load and clean employee and job data using **Pandas**
- ✅ Store cleaned data in a **relational database**
- ✅ Use **SQL** to compute key metrics:
  - Attrition Rate
  - Average Tenure
  - Department & Gender-wise Attrition
  - Role Stability
- ✅ Create visualizations for:
  - Attrition distribution
  - Job role comparison across 1 Year, 6 Months, and 1 Month
  - Demographic insights

---

## 📈 Key KPIs & Formulas

| KPI                    | Formula                                          |
|------------------------|--------------------------------------------------|
| Attrition Rate         | `(Number of Leavers / Total Employees) * 100`   |
| Average Tenure         | `AVG(YearsAtCompany)`                            |
| Role Stability         | `AVG(YearsInCurrentRole) GROUP BY JobRole`      |
| Department Attrition   | `Attrition Rate GROUP BY Department`            |
| Gender-wise Attrition  | `Attrition Rate GROUP BY Gender`                |

---

## 📊 Visual Insights

The project includes **3 time-based attrition graphs**:
- 1-Year Trend
- 6-Month Trend
- 1-Month Spike View

These charts help management understand when and why attrition may be increasing in specific job roles.

---

## 📁 Folder Structure

📂 hr-attrition-analysis/
│
├── 📊 analysis/
│ ├── attrition_trends.ipynb
│ └── sql_queries.sql
│
├── 📁 data/
│ └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── 📈 visualizations/
│ └── attrition_graphs.png
│
├── requirements.txt
└── README.md

