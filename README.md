# Tesla-Stock-Analysis


---

# 📊 Tesla Stock Analytics Dashboard — Power BI Project 

## 🧩 Project Overview

This documentation provides a detailed analysis of the **Tesla Analytics Dashboard** built using **Power BI**.
The dashboard consolidates **sales**, **production**, **geographic**, and **customer** data to deliver actionable insights that support strategic decision-making.

---

## 🎯 Objectives

The project aims to:

* Analyze Tesla’s sales performance trends
* Identify strong and weak regional markets
* Compare production output against customer demand
* Evaluate vehicle model performance
* Understand customer behavior and retention
* Provide a unified, interactive dashboard for business insights

---

## 🗂️ Data Sources

The dataset consists of:

* **Sales Data:** revenue, quantity sold, discounts
* **Production Data:** units produced, production utilization
* **Customer Data:** demographics, purchase channels
* **Geographic Data:** regions, states
* **Calendar Table:** used for DAX time-intelligence calculations

---

## 🛠️ Data Cleaning & Transformation

Performed using **Power Query**:

* Removed duplicates and empty rows
* Standardized date, currency, and text formats
* Split composite location fields into structured geographic levels
* Created conditional and calculated fields for better analysis
* Built a complete **Date Table** for time-intelligence functions

---

## 📐 Data Modeling

A **Star Schema** was designed to ensure efficient reporting and performance.

### **Fact Tables**

* `FactSales`
* `FactProduction`

### **Dimension Tables**

* `DimCustomer`
* `DimProduct`
* `DimLocation`
* `DimDate`

Relationships were created using **one-to-many** links from dimensions to fact tables, ensuring a clean and optimized data model flow.

---

## 🧮 DAX Measures

Key performance measures include:

* **Total Sales**
* **Total Quantity**
* **Average Price**
* **Year-over-Year (YoY) Growth**
* **Total Production**
* **Demand vs Production**

These measures support comparative, trend, and performance-based analytics across the dashboard.

---

## 📊 Dashboard Visuals

The Power BI dashboard includes the following analytical views:

### **1. Sales Analytics**

* Trend lines for monthly and yearly performance
* KPI cards (Sales, Orders, Quantity, Avg Price)

### **2. Regional Performance**

* Geographic maps
* Regional ranking charts

### **3. Model Performance**

* Vehicle model comparison (Model S, 3, X, Y)
* Performance contribution to overall sales

### **4. Production vs Demand**

* Visual comparison of units produced vs units ordered
* Capacity utilization indicators

### **5. Customer Insights**

* Demographic breakdowns
* Behavior and retention patterns

---

## 🔍 Key Insights

* Sales show a **strong upward trend**, driven by Model 3 and Model Y
* Regional performance is **highly varied**, revealing growth opportunities
* Production **occasionally falls short of demand**, indicating bottlenecks
* Customer retention is improving, showing increased brand loyalty
* Profitability differs across models due to cost and demand variations

---

## 💡 Recommendations

* Expand production capacity for high-demand models
* Strengthen logistics and distribution in low-performing regions
* Use demographic trends to optimize marketing strategies
* Improve supply chain efficiency to reduce delays
* Enhance customer retention and loyalty programs

---

## 🚀 Conclusion

The **Tesla Analytics Dashboard** provides a robust and comprehensive analytical framework that supports **operational**, **strategic**, and **financial** decision-making through Power BI.
Its insights help stakeholders understand performance patterns, identify opportunities, and optimize business processes.

