# 📊 Employee Attrition Analysis Dashboard

## 🎯 Objective

The goal of this project is to identify the key factors driving employee attrition and provide actionable insights to improve employee retention. This interactive Power BI dashboard equips HR professionals with the ability to monitor workforce trends and make informed, data-driven decisions.

---

## 🚀 Project Highlights

Throughout this project, the following key tasks were accomplished:

- Explored HR data to uncover meaningful patterns and trends
- Built dynamic, interactive dashboards to showcase critical HR metrics
- Delivered actionable recommendations to support strategic HR planning

---

## 🔄 Workflow Overview

### 1. Data Collection

- Imported raw `.csv` dataset into **Power BI**
- Utilized **Power Query Editor** for data preprocessing

### 2. Data Cleaning

- Removed empty columns, duplicate records, and errors
- Renamed columns for improved readability and consistency
- Applied appropriate data types using auto-detection features

### 3. Data Processing

- Created a new column `AttritionCount` using conditional logic:  
  `IF Attrition = "Yes" THEN 1 ELSE 0`
- Defined the **Attrition Rate** metric using DAX:  
  `Attrition Rate = (SUM(AttritionCount) / SUM(EmployeeCount)) * 100`

### 4. Data Analysis & Visualization

- Designed diverse visual elements:
  - **KPIs**
  - **Bar Charts**
  - **Pie/Donut Charts**
  - **Tables & Matrix Visuals**
  - **Slicers** for interactivity
- Applied filters for deep-dive analysis by:
  - Department
  - Education Field
  - Age Group
  - Gender
  - Business Travel Type

---

## 🔍 Key Business Questions Addressed

- What is the **total employee count**?
- What are the **average age** and **average salary** of employees?
- What is the **gender-wise attrition count**?
- How many years do employees typically work at the company?
- Which **department** has the most employees?
- What is the **gender distribution** across the company?
- Which **education field** has the largest workforce?
- What type of **business travel** is most common?

---

## 📌 Features & Learnings

- **Calculated Fields**: For `Attrition Rate` and `Active Employees`
- **Matrix Visuals**: Used to display job satisfaction ratings
- **Donut & Pie Charts**: To visualize gender and education field distributions
- **Bar & Clustered Charts**: To compare departments, job roles, and age groups
- **KPI Cards & Slicers**: For high-level metric tracking and dynamic filtering

---

## 📈 Summary of Insights

- **Total Employees**: 1,470
- **Attrition Count**: 237 employees left the company
  - **By Gender**: 150 males vs. 87 females
- **Departmental Attrition**:
  - **Research & Development** had the highest attrition rate (56.13%)
- **Education Field Impact**:
  - **Life Sciences** showed the highest attrition among fields
- **Job Role Impact**:
  - **Sales roles** experienced the highest attrition
- **Education Level Attrition**:
  - Employees with **High School education** had the highest attrition rate (18.24%)
- **Age Group Trends**:
  - The **25–34 age group** had the highest attrition count (112 employees)

---

## 🧠 Conclusion

This dashboard empowers HR teams to go beyond static reports by offering dynamic insights into employee turnover. By identifying high-risk segments and underlying trends, it enables proactive strategies to boost employee satisfaction and retention.

![preview](https://github.com/ShreyasreeBhattacharya/HR-ANALYTICS-DASHBOARD/blob/main/dashboard.png)
