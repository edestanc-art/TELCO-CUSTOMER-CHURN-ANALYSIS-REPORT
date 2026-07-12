# TELCO-CUSTOMER-CHURN-ANALYSIS-REPORT
# 📊 Telco Customer Churn Analysis

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

</p>

---

## 📖 Table of Contents

- Project Overview
- Business Problem
- Objectives
- Dataset
- Tools & Technologies
- Project Workflow
- Data Cleaning
- Exploratory Data Analysis
- Customer Segmentation
- Key Visualizations
- Key Findings
- Business Recommendations
- Repository Structure
- Future Improvements
- Author

---

# 📌 Project Overview

Customer churn is one of the biggest challenges facing telecommunication companies. Losing customers reduces revenue and increases acquisition costs.

This project analyzes customer data to identify the major drivers of churn using **Python**, **Pandas**, **NumPy**, and **Matplotlib**. Through data cleaning, exploratory data analysis (EDA), customer segmentation, and visualization, the project provides insights that can support data-driven customer retention strategies.

---

# 💼 Business Problem

The telecommunications company wants to understand:

- Which customers are most likely to churn?
- Which customer segments have the highest churn rates?
- How do contract type, tenure, payment method, and monthly charges influence churn?
- What actions can improve customer retention?

---

# 🎯 Project Objectives

- Clean and preprocess the dataset.
- Explore customer demographics and service usage.
- Analyze churn patterns.
- Segment customers based on tenure.
- Create meaningful visualizations.
- Generate actionable business recommendations.

---

# 📂 Dataset

The dataset contains customer information including:

- Customer ID
- Gender
- Senior Citizen
- Partner & Dependents
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Customer Tenure
- Customer Churn

**Dataset:** IBM Telco Customer Churn Dataset

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|-------|----------|
| Python | Programming |
| Pandas | Data Cleaning & Analysis |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Google Colab | Development Environment |

---

# 🔄 Project Workflow

```text
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Customer Segmentation
      │
      ▼
Churn Analysis
      │
      ▼
Business Insights
      │
      ▼
Business Recommendations
```

---

# 🧹 Data Cleaning

The following preprocessing tasks were completed:

- Checked for missing values
- Handled missing values in **Total Charges**
- Standardized column names
- Verified data types
- Checked for duplicate records
- Created tenure groups for customer segmentation

---

# 📈 Exploratory Data Analysis

The analysis covered:

- Summary Statistics
- Mean, Median & Mode
- Distribution Analysis
- Histograms
- Boxplots
- Correlation Analysis
- Customer Segmentation
- Churn Analysis

---

# 👥 Customer Segmentation

Customers were grouped based on tenure into:

- 0–12 Months
- 13–36 Months
- 37+ Months

This segmentation was visualized using a Doughnut Chart to understand customer distribution across different lifecycle stages.

---

# 📊 Key Visualizations

Include screenshots from your notebook.

Example:

```markdown
## Customer Churn Distribution

![Churn Distribution](images/churn_distribution.png)

---

## Customer Segmentation by Tenure

![Tenure Distribution](images/customer_segmentation_tenure.png)

---

## Churn by Contract Type

![Contract Type](images/contract_churn.png)

---

## Churn by Payment Method

![Payment Method](images/payment_method_churn.png)

---

## Correlation Matrix

![Correlation Matrix](images/correlation_heatmap.png)
```

---

# 🔍 Key Findings

The analysis revealed several important insights:

- Customers on **month-to-month contracts** experienced the highest churn rates.
- Customers with **shorter tenure** were more likely to leave.
- **Monthly Charges** and **Contract Type** were among the strongest factors associated with churn.
- Customers using **Electronic Check** showed higher churn rates.
- Customer churn generally decreased as tenure increased.

---

# 💡 Business Recommendations

Based on the analysis, the following recommendations are proposed:

- Encourage customers to adopt longer-term contracts.
- Strengthen onboarding and engagement programs for new customers.
- Provide personalized retention offers for customers at high risk of churning.
- Promote value-added services such as Tech Support and Online Security.
- Review pricing strategies for customers with higher monthly charges.

---

# 📁 Repository Structure

```
telco-customer-churn-analysis/
│
├── data/
├── notebooks/
├── images/
├── reports/
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🚀 Future Improvements

- Develop predictive models using:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
- Build an interactive Power BI dashboard.
- Deploy the project as a Streamlit web application.

---

# 👨‍💻 Author

**Ede**

**Statistics Graduate | Google Data Analytics Professional Certificate | Aspiring Data Analyst & Business Intelligence Analyst**

📧 Email: *(Your Email)*

💼 LinkedIn: *(Your LinkedIn URL)*

🐙 GitHub: *(Your GitHub URL)*

---

⭐ If you found this project useful, consider giving it a star!