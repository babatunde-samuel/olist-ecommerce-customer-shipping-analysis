# E-commerce Customer & Shipping Performance Analysis

## 📊 Project Overview

This project analyses e-commerce customer, order, seller and shipping data to identify purchasing patterns and evaluate delivery performance.

The analysis was conducted using the Olist e-commerce dataset and followed an end-to-end data analytics workflow:

**Data Cleaning → Data Transformation → Data Modelling → Analysis → Visualisation → Insights → Recommendations**

---

## 🎯 Business Problem

E-commerce businesses need reliable information about customer orders and delivery performance to understand customer behaviour, monitor operational performance and identify areas for improvement.

This project uses historical e-commerce data to analyse customer orders and shipping performance and communicate the findings through an interactive Power BI dashboard.

---

## 🎯 Project Objectives

The analysis aimed to:

* Analyse customer ordering and purchasing patterns.
* Evaluate order and delivery performance.
* Examine delivery times and shipping-related patterns.
* Identify variations in performance across sellers and other relevant categories.
* Develop key performance indicators for monitoring e-commerce performance.
* Present findings through an interactive Power BI dashboard.
* Provide data-driven insights and recommendations.

---

## 📁 Dataset

The project uses the real Olist Brazilian e-commerce dataset.

The dataset contains information relating to areas such as:

* Customers
* Orders
* Products
* Sellers
* Payments
* Reviews
* Order delivery dates
* Product categories
* Geographic information

The original data was distributed across multiple related tables, which were cleaned and combined during the data preparation stage.

---

## 🧹 Data Cleaning & Preparation

The raw data was prepared using Excel and Power Query.

Key data preparation activities included:

* Reviewing the structure and quality of the source tables.
* Identifying missing values.
* Checking and correcting data types.
* Cleaning and standardising fields.
* Reviewing date and datetime columns.
* Merging related datasets.
* Creating the required analytical fields.
* Checking the resulting dataset for consistency.
* Preparing the final dataset for Power BI analysis.

Special attention was given to delivery-date fields because some orders did not contain completed delivery dates.

---

## 🔄 Data Transformation

Power Query was used to transform and combine the source tables into a dataset suitable for analysis.

The transformation process included:

1. Importing the source tables.
2. Reviewing column names and data types.
3. Cleaning relevant fields.
4. Handling missing values appropriately.
5. Merging related tables.
6. Creating delivery-related calculations.
7. Reviewing the merged dataset.
8. Loading the cleaned data into the analytical model.

---

## 🧩 Data Modelling

The cleaned data was loaded into Power BI and structured into an analytical model.

Relationships between relevant entities were established to allow customer, order, seller, product and shipping information to be analysed together.

---

## 📐 DAX Measures

DAX was used to create analytical measures and KPIs required for the dashboard.

Examples of measures included calculations for:

* Total Orders
* Total Customers
* Total Sellers
* Delivery Performance
* Average Delivery Time
* Other project-specific KPIs

The measures were designed to support interactive filtering and analysis within the dashboard.

---

## 📊 Dashboard

The final Power BI dashboard provides an interactive view of the key findings from the analysis.

### Dashboard Preview

![Olist E-commerce Dashboard](Dashboard/final-dashboard.png)

The dashboard enables users to explore the data using visualisations, KPIs and filters.

### Key Dashboard Areas

* Order performance
* Customer analysis
* Shipping and delivery performance
* Seller performance
* Trends over time

---

## 🔎 Key Insights

The analysis identified patterns in customer orders, seller activity and delivery performance.

The dashboard was used to identify areas where delivery performance varied and to examine patterns across different categories and periods.

The specific findings and numerical values are presented in the final dashboard and supporting analysis.

---

## 💡 Recommendations

Based on the analysis, potential business actions include:

* Monitor delivery performance regularly using defined KPIs.
* Investigate categories or sellers associated with weaker delivery performance.
* Monitor delivery timelines against expected delivery dates.
* Use historical order data to identify operational patterns.
* Continue tracking customer and shipping performance through interactive reporting.

---

## 🛠️ Tools Used

| Tool        | Purpose                              |
| ----------- | ------------------------------------ |
| Excel       | Initial data handling and analysis   |
| Power Query | Data cleaning and transformation     |
| Power BI    | Data modelling and visualisation     |
| DAX         | Measures and analytical calculations |

---

## 📌 Skills Demonstrated

* Data cleaning
* Data transformation
* Data modelling
* Power Query
* DAX
* KPI development
* Data visualisation
* Dashboard design
* Business analysis
* Data storytelling
* Insight generation
* Recommendation development

---

## 📂 Project Structure

```text
├── Dataset
├── Excel
├── Power_Query
├── PowerBI
├── DAX
├── Dashboard
├── Documentation
└── README.md
```

---

## 👤 Author

**Babatunde Samuel**

Junior Data Analyst

Skills: Excel | Power Query | Power BI | DAX | SQL

---
