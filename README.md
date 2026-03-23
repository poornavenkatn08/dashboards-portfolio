# 📊 Data Analytics Dashboard Portfolio

Welcome to my portfolio of interactive dashboards created using **Tableau** and **Power BI**, built from real-world datasets to provide data-driven insights. These projects demonstrate my ability to perform end-to-end data analytics, from data wrangling to visualization and storytelling.

---

## 🔴 Tableau Dashboard: SaaS Customer Churn Analytics

📁 File: `SaaS Customer Churn Analytics Dashboard.twbx`  
📊 Dataset: `master_engineered.csv`, `at_risk_customers.csv`, `feature_importance.csv`, `model_comparison.csv`

🔍 **Description:**  
Designed a 4-page interactive Tableau dashboard analyzing churn patterns for RavenStack, an AI SaaS startup with 500 accounts across 5 relational tables (33,000+ records). Integrated ML prediction outputs (Random Forest, 85.73% AUC) to create actionable at-risk customer rankings and revenue impact visualizations.

✨ **Key Features:**
- Executive overview with 5 KPI cards (accounts, churn rate, MRR lost, satisfaction, tenure)
- Customer segmentation heatmap (Industry × Plan Tier churn rates)
- Treemap visualizing $1.2M MRR lost by churn reason
- Behavioral deep dive comparing churned vs retained across 6 metrics
- Engagement score distribution showing clear churn pattern at low engagement
- ML-powered at-risk customer table ranked by churn probability
- Risk level distribution with MRR at risk by severity
- Top 15 feature importance chart from Random Forest model
- Interactive cross-filters by Plan Tier, Industry, and Churn Label

📈 **Key Insights:**
| Insight | Value |
|---------|-------|
| Total Accounts Analyzed | 500 (across 5 industries) |
| Overall Churn Rate | 22.7% (110 accounts lost) |
| Total MRR Lost | $1.2M |
| Worst Segment | DevTools Enterprise (45.5% churn) |
| Best Acquisition Channel | Partner referrals (12.8% churn) |
| Worst Acquisition Channel | Event referrals (34.5% churn) |
| #1 Churn Driver (ML) | Product error rate |
| Active Accounts at Medium Risk | 123 ($1.1M MRR at risk) |
| Best Model | Random Forest (85.73% AUC, 92.31% Precision) |

🖼️ **Preview:**  
![SaaS Churn Dashboard - Executive Overview](https://raw.githubusercontent.com/poornavenkatn08/dashboards-portfolio/main/05_saas-churn-analytics/screenshots/dashboard_1_executive_overview.png)

🔗 **Live Demo:**  
[View on Tableau Public](https://public.tableau.com/app/profile/poorna.venkat.neelakantam/viz/SaaSCustomerChurnAnalyticsDashboard/Homepage)

🔗 **Related Work:**
- [Python ML Analysis (Random Forest, XGBoost)](https://github.com/poornavenkatn08/Python_Pandas-Data-Analysis-Portfolio)
- [SQL Queries (16 business queries across 5 tables)](https://github.com/poornavenkatn08/SQL-Projects)

---

## 🟢 Tableau Dashboard: E-Commerce Customer Analytics

📁 File: `E-Commerce Customer Analytics Dashboard.twbx`  
📊 Dataset: `rfm_analysis_with_id.csv`, `monthly_trend.csv`, `customer_geography.csv`

🔍 **Description:**  
This Tableau dashboard analyzes 96,477 customers and 100,000+ orders from a Brazilian e-commerce platform. It performs RFM (Recency, Frequency, Monetary) segmentation to identify high-value customers, at-risk segments, and revenue opportunities.

✨ **Key Features:**
- Customer segment distribution treemap (10 segments)
- Revenue analysis by customer segment (R$15.4M total)
- Monthly revenue and order trend analysis (2016-2018)
- RFM scatter plot showing segment positioning
- Interactive filtering across all visualizations

📈 **Key Insights:**
| Insight | Value |
|---------|-------|
| Total Customers Analyzed | 96,477 |
| Lost Customer Revenue | R$ 2.9M (recovery opportunity) |
| At-Risk Customers | 12,039 (need retention campaigns) |
| Champion Customers | 6,160 (VIP program candidates) |

🖼️ **Preview:**  
![E-Commerce Dashboard](https://raw.githubusercontent.com/poornavenkatn08/dashboards-portfolio/main/04_ecommerce-customer-analytics/screenshots/ecommerce_dashboard.png)

🔗 **Live Demo:**  
[View on Tableau Public](https://public.tableau.com/app/profile/poorna.venkat.neelakantam/viz/E-CommerceCustomerAnalyticsDashboard/Dashboard1)

🔗 **Related Work:**
- [Python RFM Analysis](https://github.com/poornavenkatn08/Python_Pandas-Data-Analysis-Portfolio)
- [SQL Project & Queries](https://github.com/poornavenkatn08/SQL-Projects/tree/main/02-Ecommerce-Customer-Analytics)

---

## 🟣 Tableau Dashboard: Airbnb Market Trends & FinTech Payments Analytics

📁 File: `AirBnb Full Project.twb`, `FinTech Payment Analytics Dashboard.twbx`  
📊 Dataset: `Tableau Full Project.xlsx`

🔍 **Description:**  
This Tableau dashboard analyzes Airbnb listings to uncover pricing patterns, popular neighborhoods, and host trends. It helps stakeholders identify profitable locations and optimize listings.

✨ **Key Features:**
- Interactive heatmaps and bar charts
- Filters by room type, neighborhood, host type
- Price vs. availability and review trends
- Host performance metrics

🖼️ **Preview:**  
![Airbnb](https://github.com/user-attachments/assets/a86a49fb-5e9f-43fe-bfdb-bd26694cbb2f)

🔗 **Live Demo:**  
[View on Tableau Public](https://public.tableau.com/app/profile/poorna.venkat.neelakantam/vizzes)

📥 **Downloads:**
- [Airbnb Dashboard (.twb)](./AirBnb%20Full%20Project.twb)
- [Excel Dataset (.xlsx)](./Tableau%20Full%20Project.xlsx)

---

## 🔵 Power BI Dashboard: Healthcare Insights

📁 File: `Power Bi Dash Board.pbix`  
📊 Dataset: `modified_healthcare_dataset.csv`

🔍 **Description:**  
This Power BI dashboard visualizes healthcare data to identify disease distribution patterns across different demographics. It's designed for hospital administrators and policymakers to monitor healthcare trends and improve resource allocation.

✨ **Key Features:**
- Disease prevalence by blood type and gender
- Filters for medical condition, admission type, and insurance provider
- Length of stay and billing analysis
- Dynamic KPIs with drill-through capabilities

🖼️ **Preview:**  
![Hospital Insights](https://github.com/user-attachments/assets/99f15fc0-f084-4234-942f-6c36f46ffe93)

📥 **Downloads:**
- [Power BI File (.pbix)](./Power%20Bi%20Dash%20Board.pbix)
- [CSV Dataset](./modified_healthcare_dataset.csv)

---

## 🧠 Skills Demonstrated

| Skill | Tools |
|-------|-------|
| Data Cleaning & Transformation | Python, Pandas, Excel |
| Customer Segmentation | RFM Analysis, K-Means Clustering |
| Churn Prediction & ML Integration | Scikit-learn, XGBoost, Random Forest |
| Dashboard Storytelling | Tableau, Power BI |
| DAX for Calculated KPIs | Power BI |
| Interactive Visualizations | Filters, Drill-through, Actions, Cross-filters |
| Data Preparation | SQL, Excel, CSV |
| Multi-Source Dashboard Design | 4 CSV data sources in single Tableau workbook |

---

## 📊 Dashboard Summary

| Project | Tool | Dataset Size | Key Metric |
|---------|------|--------------|------------|
| SaaS Customer Churn Analytics | Tableau | 33K+ records (5 tables) | $1.2M MRR lost, 85.73% AUC prediction model |
| E-Commerce Customer Analytics | Tableau | 100K+ orders | R$2.9M revenue opportunity |
| Airbnb Market Trends | Tableau | 48K+ listings | Price optimization insights |
| FinTech Payments Analytics | Tableau | 50K+ transactions | Payment trend analysis |
| Healthcare Insights | Power BI | 10K+ records | Disease distribution patterns |

---

## 📬 Contact

Let's connect! I'm open to collaboration and job opportunities in data analytics and visualization.

📧 pvneelakantam@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/pneelakantam/)  
💻 [GitHub](https://github.com/poornavenkatn08)  
📊 [Tableau Public](https://public.tableau.com/app/profile/poorna.venkat.neelakantam)
