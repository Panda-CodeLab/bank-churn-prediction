# Bank Customer Attrition Prediction

## 📌 Business Problem
Customer attrition impacts revenue and trust in retail banking.  
The objective of this project is to **predict which customers are at risk of leaving** so the bank can proactively engage them with retention strategies.  
Target: reduce attrition by 10% over the next 12 months.

---

## 📝 Jira-Style User Story
**As a** Product Owner in Retail Banking  
**I want** a predictive model that identifies customers at risk of attrition  
**So that** we can proactively engage them with retention offers and reduce churn  

**Acceptance Criteria:**
- Model achieves at least 80% accuracy.  
- Predictions are explainable (key churn drivers identified).  
- Outputs are consumable via API for CRM integration.  
- Dashboard shows churn risk distribution across demographics and product categories.  

---

## 📄 Requirements
**Scope:**
- Use historical customer data (demographics, account activity, transaction behavior).  
- Build a churn prediction model.  
- Deploy outputs into CRM systems.  
- Provide dashboards for business stakeholders.  

**Key Metrics:**
- Attrition rate reduction (target: 10%).  
- Model performance (AUC > 0.80, precision > 0.75).  
- Intervention success rate (percentage of high-risk customers retained).  

**Constraints:**
- Must comply with data privacy and governance standards.
- Model must be interpretable for regulatory review.
- Deployment must integrate with existing APIs and CRM workflows.

**Stakeholders:**
- Product Owner (Retail Banking)
- Risk Management Team
- Data Engineering Team
- Data Science Team

---

## ⚙️ Workflow
1. **Business framing & requirements gathering**  
2. **Data quality checks** (missing values, anomalies, class balance)  
3. **EDA** (churn vs. non-churn patterns)  
4. **Feature engineering** (transaction frequency, utilization ratios)  
5. **Modeling** (Logistic Regression, Random Forest, XGBoost)  
6. **Deployment** (FastAPI/Flask + Docker + MLflow)  
7. **Dashboard** (Power BI or Streamlit)  

---

## 📊 Results
- Model performance metrics (AUC, precision, recall).  
- Key churn drivers: inactivity months, transaction count, utilization ratio.  

---

## 💡 Business Impact
Reducing churn by 10% could save millions annually in retained revenue and improve customer trust.  

---
