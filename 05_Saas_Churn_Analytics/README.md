# SaaS Customer Churn Analytics Dashboard

## 📊 Dashboard Overview

Designed a **4-page interactive Tableau dashboard** analyzing churn patterns, customer segmentation, behavioral drivers, and ML-powered risk predictions for RavenStack, an AI SaaS startup with 500 accounts and $1.2M+ MRR at risk.

**Tool:** Tableau Public  
**Data Sources:** 4 CSVs (master analytics, at-risk scores, feature importance, model comparison)  
**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/poorna.venkat.neelakantam/viz/SaaSCustomerChurnAnalyticsDashboard/Homepage)

---

## 🖥️ Dashboard Pages

### Page 1: Executive Overview
*"How bad is our churn problem?"*

| Visual | Insight |
|--------|---------|
| KPI Cards | 500 accounts, 22.7% churn rate, $1.2M MRR lost, 2.28 avg satisfaction |
| Donut Chart | 110 churned vs 390 retained — visual split |
| Churn by Plan Tier | Pro tier churns highest (25.2%), Basic lowest (19.3%) |
| Monthly Churn Trend | Churn accelerated sharply in late 2024 |

### Page 2: Customer Segmentation
*"WHO is churning?"*

| Visual | Insight |
|--------|---------|
| Heatmap (Industry × Plan) | DevTools Enterprise churns at 45.5% — worst segment |
| Treemap (MRR by Reason) | Budget ($267K) and Support ($205K) are costliest churn reasons |
| Map (Churn by Country) | Geographic distribution across 7 countries |
| Referral Source Analysis | Event referrals churn at 34.5%, Partner referrals only 12.8% |

### Page 3: Behavioral Deep Dive
*"WHY are they churning?"*

| Visual | Insight |
|--------|---------|
| Feature Usage Comparison | Minimal difference (~27.7 vs ~27.6) — feature count doesn't drive churn |
| Support Metrics | Nearly identical for churned vs retained — churn is NOT a support problem |
| Upgrade/Downgrade Pattern | Retained customers upgrade 64% vs churned 58.8% — upgrades signal loyalty |
| Engagement Score Distribution | Clear pattern: low engagement (< 0.40) concentrates churned customers |

### Page 4: Prediction & Action
*"WHAT do we do about it?"*

| Visual | Insight |
|--------|---------|
| Top 15 Feature Importance | Error rate is #1 churn driver, followed by usage duration and resolution hours |
| At-Risk Customer Table | Top 20 active accounts ranked by churn probability with risk levels |
| Risk Level Distribution | 454 Low, 123 Medium, 1 High, 0 Critical |
| MRR at Risk by Level | $3.4M Low, $1.1M Medium, $620K High risk |

---

## 🎯 Key Dashboard Insights

1. **$1.2M MRR lost** to churn — Budget and Support reasons cost the most revenue
2. **DevTools + Enterprise** segment has 45.5% churn — needs immediate investigation
3. **Event referrals** are the worst acquisition channel (34.5% churn vs 12.8% for Partners)
4. **Error rate** is the #1 predictor — product quality matters more than support quality
5. **123 active accounts** flagged as Medium risk, representing $1.1M MRR at risk
6. **Company_159** (FinTech, Pro) is the highest-risk active account at 58.7% churn probability

---

## ✨ Dashboard Features

- **Interactive Filters:** Plan Tier, Industry, Churn Label — cross-filter all charts
- **Cross-Dashboard Navigation:** 4 pages tell a complete data story
- **Color-Coded Risk:** Red = Danger/Churned, Green = Safe/Retained, Orange = Warning
- **Actionable Outputs:** At-risk customer table ready for CS team outreach

---

## 🔗 Related Work

- **SQL Analysis:** [SQL-Projects](https://github.com/poornavenkatn08/SQL-Projects)
- **Python ML Analysis:** [Python_Pandas-Data-Analysis-Portfolio](https://github.com/poornavenkatn08/Python_Pandas-Data-Analysis-Portfolio)
- **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/poorna.venkat.neelakantam/viz/SaaSCustomerChurnAnalyticsDashboard/Homepage)

---

## 📁 Files

```
SaaS-Churn-Dashboard/
├── data/
│   ├── master_engineered.csv
│   ├── at_risk_customers.csv
│   ├── feature_importance.csv
│   └── model_comparison.csv
├── screenshots/
│   ├── dashboard_1_executive_overview.png
│   ├── dashboard_2_customer_segmentation.png
│   ├── dashboard_3_behavioral_deep_dive.png
│   └── dashboard_4_prediction_action.png
└── README.md
```

---

**Dataset Credit:** RavenStack dataset by River @ Rivalytics (MIT License, fully synthetic)
