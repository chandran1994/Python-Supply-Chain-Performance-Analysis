# Supply Chain Delivery Performance Analysis

This project analyzes end-to-end delivery operations for a global e-commerce supply chain using exploratory data analysis, KPI evaluation, bottleneck detection, root cause analysis, and machine learning.

The objective is to identify the operational drivers behind late deliveries, quantify their business impact, and build a predictive system capable of identifying high-risk orders before shipment.

---

# Business Problem

The company experiences consistently high late-delivery rates across multiple regions, shipping modes, and product categories.

Late deliveries create:

- Reduced customer satisfaction
- Increased operational pressure
- Lower delivery reliability
- Profitability erosion
- Supply chain inefficiencies

---

# Project Objectives

- Analyze overall delivery performance
- Measure late-delivery impact on profitability
- Identify operational bottlenecks
- Detect root causes of delays
- Analyze time-based delay behavior
- Build a predictive machine learning model for late delivery risk
- Generate strategic recommendations for operational improvement

---

# Dataset Overview

- Total Orders Analyzed: **172,765**
- Time Period: **January 2015 – January 2018**
- Global multi-region e-commerce operations
- Includes:
  - Order information
  - Shipping modes
  - Customer segments
  - Product departments
  - Profitability metrics
  - Delivery status
  - Payment types
  - Regional logistics data

---

# Key Performance Indicators (KPIs)

| KPI | Value |
|---|---|
| Total Orders | 172,765 |
| Late Deliveries | 94,523 |
| Late Delivery Rate | 54.71% |
| On-Time Delivery Rate | 45.29% |
| Total Profit | $7.5M |
| Profit at Risk | $2.1M |
| Predictive Model Accuracy | 74% |

---

# Project Workflow

## 1. Data Cleaning & Preparation

- Missing value handling
- Datetime conversion
- Feature engineering
- Delay calculation
- Profit classification
- Outlier inspection

---

## 2. Exploratory Data Analysis (EDA)

Performed detailed analysis on:

- Delay distribution
- Profitability distribution
- Shipping mode performance
- Regional performance
- Customer segment behavior
- Department-level delays
- Payment-type bottlenecks
- Time-series delay patterns

---

## 3. Bottleneck Detection

Operational bottlenecks were analyzed across:

- Shipping modes
- Geographic regions
- Customer segments
- Order statuses
- Payment methods
- Product departments

### Major Findings

- First Class shipping had a **100% delay rate**
- Second Class shipping showed **79.8% delays**
- Standard Class significantly outperformed premium modes
- Delay patterns were systemic across all regions

Which is bad for something called “First Class.”

---

# Root Cause Analysis

Deep-dive analysis identified:

- Shipping mode misconfiguration
- Payment review delays
- Seasonal demand spikes
- Capacity planning weaknesses
- Department-specific fulfillment inefficiencies

Central Africa emerged as the highest-delay region during analysis.

---

# Time-Based Analysis

Delay trends were analyzed across:

- Months
- Days of week
- Hours of day

### Key Insights

- August, September, and December showed peak delays
- Late-evening orders had the highest delay probability
- Midday processing bottlenecks were visible

---

# Machine Learning Model

A supervised machine learning classification model was developed to predict:

```python
Late_delivery_risk = 1
```

## ML Pipeline

- Frequency encoding
- Train-test split
- SMOTE oversampling
- Random Forest Classification

---

# Model Performance

| Metric | Score |
|---|---|
| Accuracy | 74% |
| Precision (Late Orders) | 0.78 |
| Recall (Late Orders) | 0.75 |
| F1-Score | 0.74 |

The model successfully identifies high-risk deliveries before shipment and can support proactive intervention systems.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SMOTE
- Random Forest Classifier
- Jupyter Notebook

---

# Supply Chain Concepts Applied

- Delivery Performance Analytics
- Supply Chain KPIs
- Root Cause Analysis
- Logistics Bottleneck Detection
- Profitability Analysis
- Predictive Analytics
- Operational Risk Modeling
- Machine Learning Classification
- Time-Based Demand Analysis

---

# Strategic Recommendations

The analysis recommends:

1. Audit First & Second Class shipping immediately
2. Deploy predictive alert systems
3. Improve payment processing workflows
4. Build seasonal surge-capacity planning
5. Optimize shipping-mode assignment logic
6. Investigate high-delay departments
7. Reduce loss-making orders
8. Continuously retrain ML models

---

# Repository Structure

```bash
├── Analysis.ipynb
├── Report.pdf
└── README.md
```

---

# Author

**Chandran**  
Supply Chain Analytics | Data Analytics | Machine Learning Enthusiast
```
