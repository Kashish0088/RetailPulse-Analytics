# 📊 RetailPulse — AI-Powered Customer Analytics Platform

### 🚀 Project Overview
RetailPulse is an end-to-end Data Science and MLOps platform designed to help retail businesses transition from reactive guessing to predictive precision. By evaluating transactional historical logs, our system optimizes shelf inventory levels, dynamically groups consumer habits, and forecasts upcoming demand trends.

---

## 👥 Our Team & Roles
* **Kashish (Member 4)** — Project Manager & Dashboard UI Engineer
* **Arpit Dubey (Member 1)** — Data Ingestion & ETL Automation Pipeline Lead
* **Mohammed ilyas salwan (Member 2)** — Customer Segmentation & Churn Analytics Specialist
* ** Yaswanth chenna(Member 3)** — Time-Series Demand Forecasting Engineer
  
---

## 🛠️ Current Project Progress

### 🔹 Phase 1: Data Preprocessing & Profiling (Current Week)
* **Dataset Used:** `online_retail_dataset Detailed.csv` (Spanning sales historical records from 2020 through 2025).
* **Data Integrity Operations:** Handled anomaly cleaning, successfully stripped out cancellation rows (negative quantities/unit prices), dropped unlinked guest customer tokens, and calculated gross metrics.
* **Feature Engineering:** Extracted snapshot-relative indices for **Recency, Frequency, and Monetary (RFM)** values.

---

## ⚙️ Local Installation & How to Run

To test our current workspace pipeline locally, follow these steps:

### 1. Clone the Workspace
```bash
pip install -r requirements.txt'''
git clone [https://github.com/Kashish0088/RetailPulse-Analytics.git](https://github.com/YOUR_USERNAME/RetailPulse-Analytics.git)
cd RetailPulse-Analytics
