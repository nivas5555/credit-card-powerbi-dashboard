# Credit Card Power BI Dashboard

This project presents an end-to-end **Credit Card Analytics solution** built using **Power BI**, focusing on both **customer profiling** and **transaction-level insights**.  
It demonstrates data cleaning, modeling, DAX calculations, and interactive dashboard design following real-world analytics practices.

---

## Dashboards Overview

### Credit Card Customer Profile Dashboard
This dashboard focuses on **customer demographics and behavior**, helping stakeholders understand who their customers are.

**Key Insights:**
- Total number of customers
- Gender distribution (Male vs Female)
- Customer age group distribution
- Income category analysis (Low / Medium / High)
- Customer segmentation by:
  - Job role
  - Education level
  - Marital status
  - Car & house ownership
- Geographic distribution of customers (USA)

**Key KPIs:**
- Total Customers
- Average Income
- Average Customer Satisfaction Score
- Average Acquisition Cost

---

### Credit Card Transaction Dashboard
This dashboard focuses on **financial performance and transaction trends**.

**Key Insights:**
- Total transactions and total revenue
- Current week vs previous week revenue
- Week-on-week revenue trends
- Revenue by:
  - Card category (Blue, Silver, Gold, Platinum)
  - Expense type (Bills, Food, Fuel, Travel, etc.)
  - Quarter
- Transaction count by gender
- Time-based analysis using week and date slicers

**Key KPIs:**
- Total Transactions
- Total Revenue
- Current Week Revenue
- Previous Week Revenue
- Total Interest Earned

---

## Tools & Technologies Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **CSV datasets**
- **Git & GitHub** for version control

---

## Data Preparation & Transformation

- Fixed inconsistent **date formats** in transaction data
- Converted week labels (e.g., `Week-12`) into numeric week numbers
- Created custom columns for:
  - Age Group
  - Income Group
- Built proper relationships using `Client_Num`
- Created reusable **DAX measures** for KPIs and trends

---

## Key DAX Measures (Examples)

- Total Revenue
- Current Week Revenue
- Previous Week Revenue
- Week-over-Week Revenue Change
- Average Income
- Average Satisfaction Score

---

## Business Value

This project helps stakeholders:
- Identify high-value customer segments
- Understand spending behavior by category
- Track revenue trends over time
- Compare weekly performance
- Make data-driven marketing and credit strategy decisions

---



