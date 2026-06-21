# 📦 FedEx Logistics Performance Analysis

## Project Overview

This project analyses FedEx logistics shipment data to identify delivery delays, freight cost inefficiencies, and supply chain performance gaps. Using Exploratory Data Analysis (EDA), the project uncovers operational bottlenecks and provides data-driven recommendations to improve delivery reliability, reduce logistics costs, and enhance supply chain transparency.

---

## Business Problem

FedEx manages thousands of global shipments across multiple countries, vendors, and transportation modes. Delays, incomplete shipment records, and rising freight costs can negatively impact customer satisfaction and operational efficiency.

The goal of this analysis was to:

* Improve on-time delivery performance
* Reduce freight costs
* Identify shipment delay patterns
* Enhance supply chain visibility through better data quality

---

## Dataset Information

* **Records:** 10,324 shipments
* **Features:** 33 columns
* **Domain:** Global Logistics & Supply Chain
* **Data Includes:**

  * Shipment details
  * Delivery timelines
  * Freight costs
  * Vendor information
  * Country-level shipment records
  * Transportation modes

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning & Preparation

Key preprocessing steps:

* Converted date columns into datetime format
* Cleaned freight cost and weight fields
* Handled missing values
* Removed invalid shipment records
* Created new analytical features:

### Engineered Features

* Delivery Delay Days
* Lead Time
* On-Time Delivery Flag
* Total Logistics Cost
* Monthly Delivery Trend
* Delay Indicators

---

## Key Performance Indicators (KPIs)

| KPI                          | Value    |
| ---------------------------- | -------- |
| Total Shipments Analyzed     | 10,324   |
| Cleaned Records Used         | 8,279    |
| On-Time Delivery Rate        | 87.09%   |
| Average Lead Time            | 109 Days |
| Average Freight Cost         | $10,749  |
| Missing PO Date Records      | 5,225    |
| Missing Freight Cost Records | 3,632    |

---

## Key Insights

### Delivery Performance

* Overall on-time delivery rate is **87.09%**
* Air shipments achieved the highest delivery reliability
* Ocean shipments experienced the longest lead times
* Nigeria, Uganda, and Mozambique showed the highest delivery delays

### Freight Cost Analysis

* Air Charter is the most expensive shipment mode
* Heavy reliance on Air transport increases operational costs
* Several shipments showed disproportionately high freight expenses

### Data Quality Findings

* 63% of records were missing PO Sent Date information
* Freight cost data was unavailable for nearly 44% of shipments
* Lead time anomalies revealed data entry issues

---

## Business Recommendations

### Delivery Optimisation

* Improve shipment planning for high-delay regions
* Monitor vendor performance through SLA tracking
* Reduce delivery bottlenecks in critical corridors

### Cost Optimisation

* Shift non-urgent shipments to lower-cost transportation modes
* Limit Air Charter usage to emergency shipments
* Improve freight cost tracking and reporting

### Data Governance

* Enforce mandatory PO date capture
* Standardise freight cost recording
* Implement automated validation checks for shipment records

---

## Visualisations Included

* Delivery Delay Distribution
* Shipment Mode Analysis
* Freight Cost Distribution
* Vendor Performance Analysis
* Country-wise Delay Analysis
* Delivery Trend Analysis
* Correlation Analysis
* Heatmaps and Multivariate Visualisations

---

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Wrangling
* Feature Engineering
* Business Problem Solving
* Data Visualisation
* KPI Development
* Logistics & Supply Chain Analytics
* Insight Generation & Business Recommendations

---

## Project Outcome

This analysis identified critical logistics inefficiencies and data quality issues impacting FedEx operations. The findings provide actionable recommendations to improve delivery performance, reduce transportation costs, and increase supply chain visibility through better operational tracking.

---

### Repository Structure

```text
├── Data/
├── Notebooks/
├── Images/
├── README.md
└── Requirements.txt
```

---

**Author:** Prajwal N
**Role:** Aspiring Data Analyst | Data Science & AI Learner
