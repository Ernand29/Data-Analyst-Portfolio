# Retail Sales Analysis: An Interactive Power BI Dashboard

![Image](https://github.com/user-attachments/assets/531ee199-64a0-42c6-8b6d-17ebfb6675f5)

**Welcome to my Power BI portfolio!** This project showcases my end-to-end skills in data analytics, from cleaning and transforming data to building a feature-rich, interactive dashboard that delivers actionable business insights.

**Author:** Ernando Taufiq Nur Hidayat

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ernando-taufiq-nur-hidayat/)

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ernando.taufiq29@gmail.com)

---

## 📈 Interactive Power BI Report

You can interact with the live report embedded below. For a full-screen experience, click the icon.

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiMzY4MWY5ZWQtYzE5Ni00MzMwLTk3YzEtNTQ3MGQxODIzMDViIiwidCI6IjFkNTE2OWFjLWM3Y2ItNDI3NS05NzY0LWJmOGM5YzM2NGE0YyIsImMiOjEwfQ%3D%3D)

## 📝 Project Executive Summary

This project analyzes sales data from a fictional retail company to identify key trends, profit drivers, and areas for growth. The dashboard is designed to provide stakeholders with quick, data-driven answers to critical business questions.

* **Data Source:** Maven Analytics Guided Project Dataset.
* **Tools Used:** Microsoft Power BI (Power Query, DAX), Excel.

### 🎯 **Project Objectives:**
1.  Identify the best and worst-performing product categories and individual products.
2.  Analyze sales performance across different geographical locations (cities and store types).
3.  Uncover sales patterns and trends over time.

### 🔑 **Key Findings & Insights:**
* **Healthy Profitability Driven by High Volume:** The business operates with a healthy **28.6% profit margin**, but relies heavily on high-volume sales of low-cost items, resulting in a low Average Order Value (AOV) of **~$16.89**.
* **"Downtown" Store Dominance:** The "Downtown" store location is a clear outlier, contributing **56% of the total profit**, indicating successful strategies that could be replicated elsewhere.
* **Strong Seasonal Sales Peak:** A significant sales spike occurs around the year-end holiday season (Q4) and the beginning of the year (Q1), which is critical for inventory and marketing planning.

---

## 🛠️ Technical Process & Methodology

Here are the technical steps I took to complete this project:

### 1. Data Extraction, Transformation, and Loading (ETL)
* Used **Power Query** to connect to and import data from multiple CSV files.
* Performed extensive data cleaning and transformation, including:
    * Correcting data types (e.g., text to date).
    * Handling null or missing values.
    * Creating new custom columns to support deeper analysis (e.g., extracting Year and Month from a date column).

### 2. Data Modeling
* Designed an efficient **Star Schema** to optimize report performance and ensure accurate calculations.
* Established correct relationships between fact and dimension tables.
* Created a dedicated **Date Table** using DAX to enable complex time intelligence analysis.

![Image](https://github.com/user-attachments/assets/ea9c2c9c-60b9-4c1d-b0f5-5bde55bcb39e)

### 3. DAX Calculations
I wrote several dynamic **Measures** using DAX to create key business metrics. Some notable examples include:
* **Total Revenue & Profit:** `Total Revenue = SUM(Sales[Revenue])`
* **Profit Margin:** `Profit Margin = DIVIDE([Total Profit], [Total Revenue])`
* **Time Intelligence:** Used functions like `SAMEPERIODLASTYEAR` and `DATESYTD` to compare performance over time (e.g., comparing this year's sales to last year's).

### 4. Visualization & Dashboard Design
* Focused on **data storytelling**, where each visual was chosen to answer a specific business question.
* Maintained a consistent color scheme and layout to ensure a clean and intuitive User Experience (UX).
* Added interactive features like slicers, informative tooltips, and drill-through capabilities to allow for self-service analysis by the end-user.

---

## 💡 Data-Driven Business Recommendations

Based on the insights uncovered, here are several actionable recommendations:

1.  **Implement an Average Order Value (AOV) Growth Strategy:** Given the low AOV, the company should introduce **product bundling** (e.g., "Buy Toy X, get a discount on Battery Y") or "frequently bought together" recommendations at checkout.
2.  **Replicate the "Downtown" Success Model:** Conduct a deep-dive case study on the Downtown store's operations, staffing, and local marketing strategies to create a blueprint for underperforming locations like "Airport".
3.  **Diversify the "Electronics" Category:** Re-evaluate the product portfolio for the Electronics category. Consider introducing products that better match the target demographic or creating targeted promotions to boost sales volume.
