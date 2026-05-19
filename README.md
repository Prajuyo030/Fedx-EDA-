# FedEx Logistics Performance Analysis

## About the project

This project focuses on analysing logistics and shipment data from FedEx to understand delivery performance, shipment delays, freight costs, and vendor efficiency.

The main goal was to explore the data, identify patterns affecting logistics operations, and suggest improvements that could help reduce delays and optimise costs.

---

## Problem Statement

FedEx manages shipments across different countries, vendors, and transportation methods. Delays in deliveries, high freight costs, and incomplete shipment records can affect overall supply chain performance.

Using Exploratory Data Analysis (EDA), this project tries to answer questions such as:

- Which shipment modes have higher delays?
- Do certain vendors perform better than others?
- How does freight cost vary?
- Which countries experience longer lead times?
- What factors affect on-time delivery?

---

## Dataset Information

Dataset contains around 10k+ shipment records with information including:

- Country
- Vendor
- Shipment mode
- Delivery dates
- Freight cost
- Product details
- Weight
- Insurance cost
- Line item value

---

## Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

Other tools:

- Google Colab
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Cleaning & Feature Engineering

Some preprocessing steps done before analysis:

- Checked duplicate records
- Handled missing values
- Converted date columns into datetime format
- Converted numeric columns
- Created new columns such as:

`delivery_delay_days`

`Lead_Time`

`On_Time`

`total_logistics_cost`

These helped in understanding shipment performance better.

---

## Analysis Performed

The project includes:

### Univariate Analysis
Understanding distribution of individual variables

Examples:
- Delay distribution
- Freight cost distribution
- Missing values

### Bivariate Analysis
Relationship between two variables

Examples:
- Weight vs Freight cost
- Vendor vs Delivery delay
- Shipment mode vs Cost

### Multivariate Analysis

Examples:
- Country + Shipment mode + Delay
- Vendor + Lead time + On-time delivery

---

## Key Findings

Some observations from analysis:

- Overall on-time delivery rate was around **87%**
- Average lead time was approximately **109 days**
- Ocean shipment had higher delays
- Air shipment was more expensive but comparatively reliable
- Missing shipment records affected tracking quality
- Some vendors consistently performed better than others

---

## Suggestions

Based on the analysis:

- Improve the shipment documentation process
- Standardise freight cost recording
- Review underperforming vendors
- Optimise shipment mode depending on urgency and cost
- Track delays continuously using dashboards

---

## Files

```text
FedEx_EDA.ipynb      -> Complete analysis notebook
README.md            -> Project overview
dataset.csv          -> Dataset used
images/              -> Charts/screenshots
```

---

## Conclusion

This project helped me practice data cleaning, feature engineering, visualisation, and extracting business insights from logistics data.

The focus was not only on creating charts but also on understanding what those insights mean from a business perspective.

---

