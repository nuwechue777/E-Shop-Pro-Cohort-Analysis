# 📊 Customer Retention & Cohort Analysis  
*E-Shop Pro Case Study | Specialization: Sales Analytics*  

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)  
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)  
![Scikit--Learn](https://img.shields.io/badge/ML-Segmentation-orange)  
![GitHub](https://img.shields.io/badge/VersionControl-GitHub-lightgrey)  
![Status](https://img.shields.io/badge/Status-Complete-success)  

---

## 🎯 Project Objective  
The Customer Retention & Cohort Analysis project focuses on identifying patterns in customer engagement and churn to help businesses improve long-term loyalty.  

The goal is to:  
- Understand how different customer cohorts behave over time.  
- Pinpoint when engagement starts to drop.  
- Segment customers using RFM + KMeans clustering.  
- Provide **actionable steps** to reduce churn and improve retention.  

---

## 📌 Deliverables  
- ✅ **Exploratory Data Analysis Notebook** – cleaning, exploring, summarizing the dataset.  
- ✅ **Insights Report** – PDF with clear findings and visualizations.  
- ✅ **Cohort Analysis** – retention matrix & heatmap visualizations.  
- ✅ **Segmentation Analysis** – customer clustering with RFM & KMeans.  
- ✅ **Version Control** – GitHub repo with commits, branches, and clean history.  

---

## 🛠️ Tech Stack  
- **Language:** Python 3.10+  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git + GitHub  

---

## 📊 Key Insights  

### 🔹 Exploratory Data Analysis (EDA)  
- Removed **135,080 null CustomerID entries** to ensure integrity.  
- Identified **Top 5 countries** by unique customers (UK, Germany, France, Netherlands, Norway).  
- Analyzed **monthly revenue trends** → identified seasonal revenue growth patterns.  

---

### 🔹 Cohort Analysis  
- Grouped customers by **acquisition month**.  
- Built a **retention matrix** tracking activity over time.  
- Key finding: **>60% churn after the first month**.  

📑 Example Retention Pivot Table:  

| CohortMonth | 1   | 2   | 3   | 4   | 5   |  
|-------------|-----|-----|-----|-----|  
| 2010-12     | 948 | 362 | 317 | 367 | 341 |  
| 2011-01     | 421 | 101 | 119 | 102 | 138 |  
| 2011-02     | 380 | 94  | 73  | 106 | 102 |  

---

### 🔹 Segmentation (RFM + KMeans)  
- Computed **Recency, Frequency, Monetary (RFM)** features.  
- Applied **KMeans clustering** to segment customers.  
- Identified clear profiles:  

| Segment            | Profile | Strategy |  
|--------------------|---------|----------|  
• Active & Steady Buyers: Reliable customers, stable revenue
• At Risk Customers: Long time since last purchase, may churn
• High-Value VIPs: Tiny group, huge spend — top priority
• Engaged Loyalists: Growing VIPs, high frequency, strong potential
---

### 🔹 Linking Cohorts to Clusters  
- Early cohorts (2010–2011) → high inflow but many shifted to **At-Risk** quickly.  
- VIPs mostly from **older cohorts** who stayed active across multiple months.  
- Recent cohorts dominated by **New/At-Risk customers**, confirming early churn risk.  

---
