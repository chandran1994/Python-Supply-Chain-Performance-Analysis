# Supply Chain Delivery Performance Analysis & Late Delivery Risk Prediction

## Project Overview

This project analyzes end-to-end delivery operations for a global e-commerce supply chain to identify operational bottlenecks, quantify the impact of delivery delays, and develop a machine learning model capable of predicting late delivery risk before shipment.

Late deliveries affect customer satisfaction, increase operational costs, disrupt inventory planning, and reduce overall supply chain reliability. The objective of this project was to understand the root causes of delivery delays and provide data-driven recommendations to improve logistics performance.

The project combines exploratory data analysis, KPI evaluation, bottleneck detection, root cause analysis, profitability assessment, and predictive analytics to create a complete supply chain performance monitoring framework.

---

## Project Files

| File           | Objective                                                           |
| -------------- | ------------------------------------------------------------------- |
| Analysis.ipynb | Supply chain performance analysis and late delivery risk prediction |
| Report.pdf     | Business report summarizing findings and recommendations            |

---

## View Project

📓 [View Notebook](https://nbviewer.org/github/chandran1994/Python-Supply-Chain-Performance-Analysis/blob/main/Analysis.ipynb)

📊 Report.pdf

---

# Business Problem

A global e-commerce operation was experiencing consistently high late-delivery rates across multiple regions, shipping modes, and customer segments.

Late deliveries create several business challenges:

* Reduced customer satisfaction
* Increased operational pressure
* Higher logistics costs
* Lower service-level performance
* Revenue and profitability risk
* Supply chain inefficiencies

The goal was to identify the operational drivers behind delays and develop a predictive system capable of identifying high-risk orders before shipment.

---

# Analytical Workflow

```text
Raw Supply Chain Data
            ↓
Data Cleaning & Preparation
            ↓
KPI Analysis
            ↓
Exploratory Data Analysis
            ↓
Bottleneck Detection
            ↓
Root Cause Analysis
            ↓
Profitability Assessment
            ↓
Machine Learning Model
            ↓
Operational Recommendations
```

---

## Dataset Overview

The dataset contains approximately 172,000+ global e-commerce orders covering multiple regions, product categories, shipping methods, and customer segments.

### Data Included

```text
Order Information
    ├── Order Status
    ├── Delivery Status
    ├── Shipping Mode
    └── Order Dates

Customer Information
    ├── Customer Segment
    ├── Geographic Region
    └── Market

Operational Information
    ├── Delivery Times
    ├── Shipping Performance
    ├── Product Categories
    └── Logistics Metrics

Financial Information
    ├── Revenue
    ├── Profit
    └── Profitability Measures
```

---

## Data Preparation

The project began with extensive data cleaning and feature engineering.

Key preprocessing activities included:

* Missing value treatment
* Datetime conversion
* Delay calculations
* Profit classification
* Feature engineering
* Outlier inspection
* Data quality validation

These transformations created the foundation for operational and predictive analysis.

---

## KPI Analysis

Several key supply chain performance metrics were calculated to establish a baseline understanding of operational performance.

### KPIs Evaluated

```python
Late Delivery Rate

On-Time Delivery Rate

Total Orders

Total Profit

Profit at Risk

Delivery Performance Metrics
```

These KPIs provided visibility into delivery reliability and the financial impact of operational inefficiencies.

---

## Exploratory Data Analysis

The analysis investigated how delays varied across multiple operational dimensions.

### Operational Dimensions Analyzed

```python
Shipping Modes

Regions

Customer Segments

Departments

Payment Types

Order Status

Delivery Status
```

The goal was to identify patterns, bottlenecks, and operational weaknesses contributing to poor delivery performance.

---

## Shipping Mode Performance Analysis

Shipping methods were evaluated to understand their impact on delivery reliability.

### Analysis Performed

```python
Delay Rate by Shipping Mode

Order Volume by Shipping Mode

Shipping Performance Comparison
```

The analysis revealed significant differences in performance across shipping methods and highlighted operational inconsistencies that contributed to delays.

---

## Regional Performance Analysis

Geographic performance was examined to identify regions experiencing elevated delivery risk.

### Analysis Performed

```python
Regional Delay Rates

Regional Profitability

Geographic Performance Comparison

Market-Level Analysis
```

This analysis highlighted areas where logistics processes may require additional capacity, process improvements, or operational intervention.

---

## Customer Segment Analysis

Delivery performance was evaluated across customer groups to understand how service quality varied among different customer segments.

### Analysis Performed

```python
Customer Segment Performance

Delay Distribution

Revenue Contribution Analysis

Service-Level Comparison
```

Understanding customer-level delivery performance helps prioritize operational improvements where they have the greatest business impact.

---

## Product Department Analysis

Department-level performance was analyzed to identify categories experiencing disproportionate delay rates.

### Analysis Performed

```python
Department Delay Analysis

Revenue Impact Assessment

Operational Bottleneck Detection
```

This analysis helped identify operational areas requiring targeted process improvement.

---

## Profitability Impact Analysis

The relationship between delivery performance and profitability was evaluated.

### Analysis Performed

```python
Profit Distribution

Profit at Risk Analysis

Late Delivery Profit Impact

Revenue Performance Evaluation
```

The analysis quantified the financial consequences of delivery failures and highlighted the business value of improving operational performance.

---

## Root Cause Analysis

After identifying delay hotspots, a deeper investigation was performed to uncover underlying operational drivers.

### Factors Investigated

```text
Shipping Mode Configuration

Payment Processing Delays

Seasonal Demand Surges

Regional Constraints

Department-Level Bottlenecks

Operational Capacity Limitations
```

The objective was to move beyond symptom identification and understand the mechanisms contributing to delivery delays.

---

## Time-Series Analysis

Delivery performance was analyzed across different time dimensions to identify recurring operational patterns.

### Time-Based Analysis

```python
Monthly Delay Trends

Daily Delay Patterns

Hourly Performance Analysis

Seasonal Variations
```

This analysis revealed periods associated with elevated delivery risk and operational pressure.

---

## Machine Learning: Late Delivery Risk Prediction

The final stage of the project focused on developing a predictive model capable of identifying orders likely to experience delivery delays.

### Target Variable

```python
Late_Delivery_Risk

0 = On-Time Delivery

1 = Late Delivery
```

### Machine Learning Pipeline

```text
Feature Engineering
        ↓
Frequency Encoding
        ↓
Train-Test Split
        ↓
SMOTE Oversampling
        ↓
Random Forest Classification
        ↓
Prediction & Evaluation
```

### Model Objectives

The model was designed to -

* Predict late deliveries before shipment
* Support proactive intervention
* Improve delivery reliability
* Reduce operational risk
* Improve customer service performance

By identifying high-risk orders early, logistics teams can take corrective action before delays occur.

---

## Business Value

This project demonstrates how analytics and machine learning can improve supply chain visibility and operational decision-making.
