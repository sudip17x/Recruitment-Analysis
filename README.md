# Hiring-Analysis
## 📁 Hiring Analysis – Data-Driven Insights for Smarter Recruitment Decisions

![image alt](https://github.com/sudip17x/Amazon_Sales_Analysis_using_python/blob/ab849d1ffe3635a3f2dfbe4f97d120bbd5def696/Amazon%20Sales%20Dashboard%20Image.jpg)

### 📌 Overview

This project focuses on analyzing a multinational company's hiring data using **Microsoft Excel** to identify trends, patterns, and anomalies in the recruitment process. It aims to provide insights that can **optimize hiring strategies**, understand **salary distribution**, and improve **department-level resource allocation**.

### 🎯 Objectives

* Analyze gender distribution among hires.
* Understand the company’s salary structure and outliers.
* Visualize salary bands across departments and positions.
* Identify high-performing and underutilized job roles.
* Detect departmental hiring trends and alignment with business needs.

### 📊 Key Performance Indicators (KPIs)

| KPI                           | Metric                                     |
| ----------------------------- | ------------------------------------------ |
| 📈 **Hiring Rate**            | Total number of hires                      |
| 🚹 **Gender Ratio**           | % Male, % Female, % Undisclosed            |
| 💵 **Average Salary**         | With and without outliers                  |
| 🧮 **Salary Segments**        | Number of employees in each salary bracket |
| 🏢 **Top Hiring Departments** | Departments with most hires                |
| 👔 **Popular Job Tiers**      | Positions with highest/lowest hiring       |
| ⚠️ **Outlier Detection**      | Number of outliers affecting salary mean   |

### 🧰 Tech Stack

* **Microsoft Excel**: Data cleaning, functions, pivot tables, charts
* **Excel Functions Used**: `AVERAGEIFS`, `COUNTIF`, `IF`, `VLOOKUP`, `FILTER`, `QUARTILE`, etc.
* **Visualization Tools**: Pie charts, bar graphs, salary histograms

### 🔎 Methodology

#### 1. **Data Wrangling**

* Removed missing or irrelevant data
* Handled gender disclosure gaps
* Treated salary outliers using statistical limits (Q1, Q3, IQR)

#### 2. **Hiring Analysis**

* Calculated counts and percentages by gender
* Identified overall hiring volume and department-wise breakdown

#### 3. **Salary Analysis**

* Computed average salary with and without outliers
* Created class intervals for salary distribution

#### 4. **Department & Position Tier Analysis**

* Identified top hiring departments (e.g., Operations, Service)
* Analyzed hiring trends across position tiers (e.g., c5, c9, etc.)

### 📈 Visualizations

* **Bar Graphs**: Department-wise and post-wise hiring distribution
* **Pie Charts**: Gender ratio and departmental composition
* **Histograms**: Salary distributions across job tiers
* **Box Plot (Optional)**: Salary outlier detection

### 📌 Key Insights

* 🧑‍🤝‍🧑 **Gender Bias**: Majority of hires were male; 6% undisclosed
* 💵 **Salary Trends**:

  * Avg salary w/ outliers: \$49,976
  * Avg salary w/o outliers: \$49,878
  * 62% of employees earned under \$60,000
* 🏢 **Top Departments**:

  * Operations: 1843 hires
  * Service: 1332 hires
* 👔 **Position Trends**:

  * c5 & c9 had highest hires (mostly under \$40,000)
  * Positions m6, m7, n6, n9, n10 were rarely hired

---

### 🚀 Outcomes & Impact

* Improved understanding of salary bands and role-level resource allocation
* Identification of underutilized job roles and over-reliance on certain positions
* Recommendations for gender-balanced hiring strategies
* Clear visualization of hiring trends that can guide recruitment and budgeting

### 🔧 Future Improvements

* Integrate SQL or Python for scalable analysis
* Deploy an interactive dashboard (Power BI / Tableau)
* Expand dataset to include performance and tenure metrics
* Add predictive modeling for attrition or post-hire success rate


