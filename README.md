# Drug Marketing Strategy Analysis Dashboard

## 📌 Overview

This project involves the analysis and visualization of the marketing performance for a pharmaceutical company's flagship drug, **NZT-48**, using **Power BI**. The drug is used for treating chronic Lyme disease, and the company aims to evaluate the effectiveness of past marketing strategies and assess the impact of a competitor drug that entered the market in mid-2015. The analysis is based on real-world sales and marketing data across various healthcare facilities.

## 🎯 Objectives

- Estimate the **dollar-value sales** attributable to each marketing strategy.
- Analyze the **impact of a new competitor drug** on NZT-48 sales.
- Provide actionable insights to guide **future marketing budgets**.
- Identify **market penetration trends** and strategy-specific performance across accident types (hospital, pharmacy, polyclinic, private clinic).

## 📊 Dataset Description

The dataset includes the following key variables:

- `date`: Date of the sale or marketing activity.
- `accident_type`: Type of healthcare facility (Hospital, Pharmacy, Polyclinic, Private Clinic).
- `quantity`: Units of NZT-48 sold.
- `strategy`: Marketing strategy applied.
- `target_dr`: Target doctor ID.
- `total_sales`: Revenue generated per strategy.
- `competitor_presence`: Impact level of the new competitor drug.

> The dataset spans sales data for two years and includes both pre- and post-competitor market entry periods.

---

## 💼 Business Problems & Solutions

### 1. **How effective is each marketing strategy?**
   - **Solution**: Created KPIs such as **Total Sales**, **Total Quantity**, and **Avg. Sales per Strategy** to quantify strategy impact.

### 2. **How has the competitor’s drug impacted sales?**
   - **Solution**: Used bar chart comparisons to visualize **total sales with and without competitor presence** by accident type. Significant dips were observed post-mid-2015.

### 3. **Where is NZT-48 most popular?**
   - **Solution**: Built a **map visualization** of sales volume across France by accident type to assess **geographic penetration**.

### 4. **Which doctors contributed most to sales?**
   - **Solution**: Used a **treemap visualization** to analyze **total sales per doctor (target_dr)** to identify key prescribers.

### 5. **How have sales trended over time?**
   - **Solution**: Created a **line graph** showing monthly **sales trends segmented by accident type**. Patterns of seasonality and growth were analyzed.

---

## 📈 Visualizations Explained

| Visualization | Description | Purpose |
|---------------|-------------|---------|
| 💡 **KPI Tiles** | Total Quantity, Avg Sales per Strategy, and Total Sales | Provide quick snapshot of performance |
| 📊 **Bar Chart: Impact of Competitor** | Sales before and after competitor entry by accident type | Identify strategy shifts needed |
| 🌍 **Map: Market Penetration** | Location-wise sales data colored by accident type | Uncover geographical market penetration |
| 🧱 **Treemap: Sales by Target Doctor** | Size-coded doctor contribution to total sales | Identify high-impact doctors |
| 📈 **Line Chart: Sales Trend Over Time** | Month-by-month breakdown of sales | Reveal growth, seasonality, and competitor effects |

---

## 👩‍💼 Roles and Responsibilities

| Role | Responsibility |
|------|----------------|
| **Data Analyst** | Cleaned and prepared raw marketing and sales data |
| **BI Developer** | Built interactive Power BI dashboards and charts |
| **Business Consultant** | Interpreted data insights for stakeholder communication |
| **Data Scientist** | Modeled competitor impact and estimated strategy-level ROI |

---

## 🔍 Key Insights

- Marketing Strategy **4** drove the highest sales across hospitals.
- **Competitor entry** in mid-2015 led to a noticeable dip in private clinic and pharmacy segments.
- **Doctor ID 102** was the top contributor with maximum sales.
- Sales peaked in **April 2015**, showing strong seasonal trends.
- **Hospitals** were the most effective channel for NZT-48 distribution.

---

## ✅ Conclusion

The dashboard helped identify which marketing strategies performed best, both before and after the competitor drug’s launch. It provided actionable insights such as:

- Reallocating resources to hospital-targeted campaigns.
- Focusing on high-performing doctors for future marketing.
- Monitoring competitor influence more aggressively using trend tracking.

The findings will support **budget optimization**, **campaign realignment**, and **decision-making** for future marketing strategy refinement.

---

## 📁 Project Structure

