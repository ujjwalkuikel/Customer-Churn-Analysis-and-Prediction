
# 📉 Customer Churn Analysis & Prediction Dashboard

This project explores customer churn using a business intelligence dashboard, combined with predictive modeling to identify key churn drivers and help stakeholders take actionable retention steps.

---

## 🔍 Project Overview

**Goal:**  
Analyze historical customer data to uncover patterns in churn, segment at-risk groups, and predict future churn using machine learning models.

**Business Context:**  
Customer churn is a major concern for subscription-based businesses. Identifying the most vulnerable customer segments allows targeted retention strategies, improving revenue and customer lifetime value (CLTV).

---

## 🛠 Tools & Technologies

| Type | Tools |
|------|-------|
| Data Analysis | Python (Pandas, NumPy), Power BI |
| Visualization | Power BI |
| Machine Learning | Scikit-learn (Decision Tree, Random Forest) |
| Data Handling | Excel/CSV, Power Query |
| Explainability (Optional) | SHAP (for model interpretation) |

---

## 📊 Dashboard Highlights

![Churn Dashboard](./images/churn_dashboard_sample.png) <!-- Replace with your actual screenshot path -->

**Key Features:**
- High-level KPIs: Total Customers, Total Churn, Churn Rate, New Joiners
- Churn Breakdown by:
  - **Contract Type**
  - **Age Group**
  - **State**
  - **Payment Method**
  - **Internet & Service Type**
- Churn Category Analysis: Price, Competitor, Service, Others
- Service Opt-In vs Churn Table (e.g., Online Security, Premium Support)
- Gender Distribution, Tenure Groups, and State-wise Churn Rates

---

## 🤖 Machine Learning Component (Added)

**Objective:**  
Predict customer churn using classification models based on customer features.

**Models Used:**
- Decision Tree Classifier
- Random Forest Classifier

**Metrics:**
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix

**Feature Importance:**
- Identified top churn indicators like Contract Type, Tenure, and Monthly Charges using model interpretation techniques.

**Next Steps:**
- Integrate predictions into Power BI via Python visual or Streamlit app.
- Add SHAP plots to explain model decisions.

---

## 🧠 Business Insights (Examples)

- **Month-to-Month contracts** have over 40% churn — strong case for loyalty offers or long-term incentives.
- **Online Backup & Security opt-out customers** showed significantly higher churn — bundling these features could improve retention.
- **Jammu & Kashmir region** has highest churn (57.2%) — investigate service reliability or pricing strategy there.
- **Young customers (18–30)** have elevated churn rates — optimize onboarding or engagement strategies for Gen Z.

---

## 📁 Project Structure

```
Churn-Analysis/
│
├── data/
│   ├── churn_data.csv
│
├── notebooks/
│   ├── churn_analysis.ipynb
│   ├── churn_modeling.ipynb
│
├── dashboard/
│   └── churn_dashboard.pbix
│
├── images/
│   └── churn_dashboard_sample.png
│
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository  
```bash
git clone https://github.com/ujjwalkuikel/churn-analysis-dashboard.git
cd churn-analysis-dashboard
```

2. Open `churn_dashboard.pbix` in Power BI Desktop.

3. To run the ML models:  
```bash
pip install -r requirements.txt
jupyter notebook notebooks/churn_modeling.ipynb
```

---

## 📌 Key Skills Demonstrated

- Business Intelligence (Power BI, KPIs, dashboarding)
- Data Cleaning & Feature Engineering
- Classification Algorithms (Decision Trees, Random Forests)
- Model Evaluation & Interpretation
- Domain understanding of churn dynamics

---

## 📎 Related Projects

- [Insurance Premium Prediction via Clustering](https://github.com/ujjwalkuikel/insurance-premium-clustering)
- [Resume Evaluator with LLMs](https://github.com/ujjwalkuikel/resume-evaluator-llm)
- [Kidney Transplant Simulation](https://github.com/ujjwalkuikel/kidney-transplant-sim)

---

## 🧠 Data Science Fact

> In many industries, **5% reduction in churn** can lead to **25–95% increase in profit** — because retaining customers is far cheaper than acquiring new ones.

---

## 📬 Contact

**Ujjwal Kuikel**  
📧 ujjwalkuikel2002@gmail.com  
🌐 [ujjwalkuikel.com.np](http://ujjwalkuikel.com.np)  
📇 [LinkedIn](https://linkedin.com/in/ujjwalkuikel) | [GitHub](https://github.com/ujjwalkuikel)

---
