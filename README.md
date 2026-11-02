## Project name: E-Commerce Logistics Data Analytics and Delivery Optimization
# Logistics Data Analytics – Brazilian E-Commerce

## Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset by Olist to understand logistics performance, delivery delays, freight costs, customer satisfaction, and operational risks.

The project follows a four-week analytics workflow, covering data exploration, preprocessing, exploratory data analysis, predictive modeling, and logistics optimization recommendations.

## Objectives

- Analyze order and delivery performance.
- Identify factors associated with late deliveries.
- Examine freight costs and geographic distribution.
- Understand the relationship between delivery performance and customer reviews.
- Develop a machine learning model to predict delivery lead time.
- Recommend operational improvements using data-driven insights.

## Dataset

**Source:** [Brazilian E-Commerce Public Dataset by Olist – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains approximately 100,000 orders and related information about customers, sellers, products, payments, reviews, and delivery.

The original dataset is not included in this repository. Download it from Kaggle and follow the notebook's data-loading instructions.

## Project Workflow

### Week 1 – Strategic Planning and Data Exploration
- Defined the project scope and business problem.
- Identified logistics performance KPIs.
- Planned analytical approaches for delivery performance and operational efficiency.

### Week 2 – Data Collection and Preprocessing
- Loaded and examined the Olist datasets.
- Handled missing values and duplicate records.
- Investigated outliers and data-quality issues.
- Performed data transformation and scaling.
- Conducted payment reconciliation checks.

### Week 3 – Advanced Data Analysis and Visualization
- Analyzed delivery performance and delay patterns.
- Examined freight costs and product revenue.
- Investigated geographic and seller-level performance.
- Evaluated customer review scores against delivery performance.
- Created visualizations to communicate findings.

### Week 4 – Predictive Modeling and Optimization
- Developed delivery lead-time prediction models.
- Compared Linear Regression, Decision Tree, and Random Forest.
- Evaluated models using MAE, RMSE, and R².
- Conducted time-based validation and exploratory feature importance analysis.
- Developed a delay-risk classification approach for operational prioritization.

## Key Findings

- Analyzed 99,441 orders.
- Evaluated 96,470 delivered orders with the required delivery timestamps.
- Observed an 8.11% late-delivery rate in the Week 3 analysis.
- Average actual delivery duration was approximately 12.56 days.
- Average customer review score was approximately 4.09.
- The updated Random Forest model achieved a test MAE of approximately 4.20 days.
- The updated model improved test MAE by approximately 4.71% compared with the original Random Forest model.

**Note:** Predictive performance is modest. The model is intended as an exploratory decision-support prototype, not a production-ready delivery forecasting system.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Repository Structure

```text
logistic_data_analyst/
│
├── Logistics_Data_Analytics.ipynb
├── data/
│   └── processed/
├── outputs/
│   └── figures/
├── reports/
│   ├── Week_1_Report.docx
│   ├── Week_2_Report.docx
│   ├── Week_3_Report.docx
│   └── Week_4_Report.docx
├── README.md
├── requirements.txt
└── .gitignore
```

## Project Deliverables

- Complete Jupyter Notebook covering Week 1–Week 4.
- Processed datasets and reconciliation output.
- Data analysis and predictive modeling visualizations.
- Four weekly project reports.

## Limitations

- The analysis uses historical e-commerce data.
- Predictive performance is limited by the available features and dataset.
- The risk classification approach requires further validation before operational use.
- Actual road-network routing, vehicle capacity, and live traffic optimization were outside the scope of this project.

