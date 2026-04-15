# Data-Job-Salaries-Calculator-with-Excel

# 📊 Salary Analytics Dashboard (Excel)
<img width="1889" height="864" alt="image" src="https://github.com/user-attachments/assets/ee7bcee0-94f9-4c64-97ad-955a717b09a2" />

## 🧾 Project Summary

This project presents an end-to-end salary data analysis using **Microsoft Excel**, leveraging **Power Query**, **Data Modeling (Power Pivot)**, and **interactive dashboards** to uncover insights into salary trends across different job roles, countries, and employment types.

The dashboard is designed to support data-driven decision-making by transforming raw job salary data into meaningful business insights.

---

## 🎯 Business Objectives

* Analyze salary distribution across different job titles
* Compare salary trends across countries
* Identify factors influencing salary variations
* Provide an interactive dashboard for exploratory analysis

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**

  * Power Query (ETL process)
  * Power Pivot (Data Model)
  * Pivot Tables & Charts
* **Data Analysis Techniques**

  * Data Cleaning & Transformation
  * Aggregation (Median, Filtering)
  * Text-based filtering using search logic

---

## 📂 Dataset Description

The dataset contains structured job-related data, including:

* `job_title` → Role or position
* `job_country` → Location of the job
* `salary_year_avg` → Average annual salary
* `job_schedule_type` → Employment type (e.g., Full-time, Part-time)

---

## 🔄 Data Processing Workflow

### 1. Data Extraction & Cleaning

* Removed null and zero salary values
* Standardized column formats
* Filtered relevant job records

### 2. Data Transformation (Power Query)

* Applied conditional filtering using:

  * Logical conditions (`IF`)
  * Text matching (`SEARCH`)
* Structured dataset for analysis

### 3. Data Modeling (Power Pivot)

* Loaded transformed data into Data Model
* Established relationships (if applicable)
* Enabled advanced aggregation

### 4. Data Analysis

* Calculated median salary using conditional logic
* Segmented data by country and job type

### 5. Data Visualization

* Built interactive dashboard using:

  * Pivot Tables
  * Charts
  * Slicers (filters)

---

## 📈 Key Insights

> *(Sesuaikan bagian ini dengan dashboard kamu, tapi ini contoh profesionalnya)*

* Certain job roles consistently show higher median salaries across regions
* Salary distribution varies significantly between countries
* Full-time roles tend to offer higher and more stable compensation
* Filtering by job type reveals niche roles with above-average pay

---

## ⚠️ Challenges & Issues

* Encountered Data Model error:

  > *"Object reference not set to an instance of an object"*
* Complexity in maintaining consistency between Power Query steps and Data Model
* Handling dynamic filtering with multiple conditions

---

## 💡 Solutions Implemented

* Validated all column references in Power Query
* Rebuilt Data Model connections when necessary
* Ensured data consistency before loading into the model
* Applied structured transformation steps to avoid broken dependencies

---

## 🚀 How to Use

1. Open `salary_dashboard.xlsx`
2. Enable content/macros if prompted
3. Navigate to the dashboard sheet
4. Use slicers to filter by:

   * Job Title
   * Country
   * Job Type

---

## ⭐ Portfolio Note

This project demonstrates:

* End-to-end data analysis workflow
* Strong Excel & Power Query skills
* Ability to translate raw data into actionable insights
