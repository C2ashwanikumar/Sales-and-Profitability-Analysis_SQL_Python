# **Sales Analysis Project**

This project provides a detailed analysis of sales performance, profitability, and regional trends by leveraging datasets and solving analytical problem statements using MySQL and Python. Data was imported into a MySQL database using Python, and SQL queries were executed within Python to derive insights and actionable recommendations.

---

## **Project Highlights**

### **Part 1: Sales and Profitability Analysis**
This segment focuses on analyzing overall sales and profitability metrics across product categories to identify top-performing and underperforming segments.

#### **Key Deliverables:**
- **Data Integration:** The `List of Orders` and `Order Details` datasets were merged using SQL joins on the `Order ID` field.
- **Metrics Calculation:**
  - **Total Sales (Amount):** Computed for each category using SQL aggregate functions.
  - **Average Profit Per Order** and **Profit Margin** (Profit as a percentage of sales amount).
- **Performance Analysis:** Categories were ranked based on profitability and sales metrics to identify key drivers of performance and areas needing improvement.

---

### **Part 2: Target Achievement Analysis**
This section evaluates the target-setting process for the Furniture category, focusing on month-over-month target changes and alignment with actual performance trends.

#### **Key Deliverables:**
- **Trend Analysis:** Monthly percentage change in target sales was calculated using SQL functions.
- **Significant Fluctuations:** Unusual trends in targets were identified to pinpoint potential issues.
- **Strategic Recommendations:** Data-driven strategies were developed to align sales targets with realistic projections and historical performance trends.

---

### **Part 3: Regional Performance Insights**
This segment explores geographical trends to identify top-performing states and uncover regional disparities in sales and profitability.

#### **Key Deliverables:**
- **Top 5 States:** SQL queries identified the states with the highest order counts.
- **Metrics Calculation:**
  - **Total Sales** and **Average Profit** were calculated for these states.
- **Regional Disparities:** Differences in sales and profitability were analyzed, highlighting regions that require strategic focus.
- **Improvement Strategies:** Suggested steps to enhance sales and profitability in underperforming regions.

---

## **Features**
- **SQL-Driven Analysis:** All calculations and insights were derived using efficient SQL queries executed in Python.
- **Comprehensive Insights:** Metrics like total sales, average profit, and profit margins are presented for actionable decision-making.
- **Focus on Real Data:** Emphasis on real-world problem statements and tailored recommendations.

---

## **How the Project Was Executed**

1. **Data Import:**
   - Datasets were imported into a MySQL database using Python and Pandas.
   - SQL queries were executed within Python using the MySQL connector library.

2. **Data Cleaning and Transformation:**
   - Data inconsistencies were addressed using SQL transformations.
   - Derived fields like profit margin and monthly percentage change were computed in SQL.

3. **SQL Analysis:**
   - Queries were written to compute metrics, identify trends, and rank performance by categories, regions, and targets.




