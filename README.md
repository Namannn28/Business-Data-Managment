# Inventory Optimization and Retail Analytics using Business Data Management

## Project Overview

This project was developed as part of the **Business Data Management (BDM)** course in the **IIT Madras BS Degree Program**.

The project analyzes operational challenges faced by a retail ethnic wear store (**Tulsi Ethnic Wear**) and applies business analytics techniques to improve inventory management, operational efficiency, and competitive positioning.

The study focuses on three key business problems:

1. Inventory Optimization
2. Competitive Positioning Analysis
3. Customer Workload Distribution Analysis

---

## Business Problem

The store faced several operational challenges:

* Excess inventory accumulation
* Working capital blockage
* Increasing competition from online marketplaces
* Uneven customer workload during peak operational hours

The objective was to use data-driven analysis to identify inefficiencies and provide actionable business recommendations.

---

## Datasets Used

### 1. Sales & Purchase Data (Primary Data)

Collected directly from store transaction records.

Fields include:

* Month
* Product Category
* Purchase Value
* Sales Value
* Quantity

### 2. Competition Dataset

Collected manually from:

* Myntra
* Ajio
* Amazon

Fields include:

* Product Price
* Platform
* Price Band

### 3. Customer Workload Dataset (Primary Data)

Prepared using:

* Direct observations
* Store owner discussions

Fields include:

* Season
* Time Slot
* Workload Level

---

## Methodology

### Inventory Analysis

* ABC Analysis
* Pareto Analysis
* Economic Order Quantity (EOQ)
* Safety Stock Calculation
* Reorder Point (ROP)

### Competition Analysis

* Price Band Classification
* Competitor Benchmarking
* Market Positioning Analysis

### Workload Analysis

* Seasonal Workload Comparison
* Workload Heatmap
* Customer Flow Analysis

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Excel
* Google Colab

---

## Key Findings

### Inventory Analysis

* Total inventory investment analyzed: ₹11.8L+
* Kurti Sets contributed approximately 50.3% of total inventory investment
* Excess inventory accumulation of nearly ₹1.52L identified during February 2026

### Inventory Optimization

* EOQ: 111 Units
* Safety Stock: 22 Units
* Reorder Point: 62 Units

### Competition Analysis

* Myntra and Ajio showed stronger concentration of premium-priced products
* Amazon demonstrated greater concentration in lower-price ranges
* Tulsi primarily competes within the medium and upper-medium price segment

### Workload Analysis

* Winter workload peaks between 3 PM – 7 PM
* Summer customer flow shifts towards 6 PM – 9 PM
* Morning periods remain comparatively underutilized

---

## Business Recommendations

### Inventory Management

* Implement EOQ-based procurement planning
* Monitor Class A inventory categories monthly
* Introduce demand-driven purchasing practices

### Competitive Positioning

* Focus on product differentiation
* Introduce selective seasonal promotions
* Improve customer experience rather than competing solely on price

### Operational Efficiency

* Allocate staff according to workload intensity
* Shift backend activities to low-workload periods
* Improve workforce scheduling during peak hours

---

## Project Structure

```text
├── Dataset
│   ├── Sales_Data.xlsx
│   ├── Purchase_Data.xlsx
│   ├── Competition_Data.xlsx
│   └── Workload_Data.xlsx
│
├── Notebook
│   └── BDM_Project.ipynb
│
├── PPT
│   └── Final_Presentation.pptx
│
├── Report
│   └── Final_Report.pdf
│
└── README.md
```

---

## Learning Outcomes

This project demonstrates practical application of:

* Business Analytics
* Inventory Management
* Data Visualization
* Retail Operations Analysis
* Business Decision Support Systems
* Data-Driven Recommendation Frameworks

---

## Author

**Naman**
IIT Madras BS Degree Program
Business Data Management Project
