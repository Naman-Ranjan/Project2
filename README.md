# Customer Shopping Behavior Analysis

## 📊 Project Overview

An end-to-end data analytics project analyzing customer shopping behavior to identify purchasing patterns, customer segments, product preferences, and factors influencing purchase decisions.

The project demonstrates a complete analytics workflow using **Python, SQL, and Power BI**, starting from raw customer transaction data and ending with an interactive business intelligence dashboard and actionable recommendations.

### Business Objective

The analysis aims to answer key business questions such as:

* Which customer segments contribute the most revenue?
* What products and categories are most frequently purchased?
* How do purchase patterns vary across customer demographics?
* What factors are associated with higher customer spending?
* Which customers show characteristics of high-value or loyal customers?
* What business actions could improve customer retention and revenue?

---

## 🛠️ Tools & Technologies

* **Python** — Data cleaning, preprocessing and exploratory data analysis
* **Pandas** — Data manipulation and transformation
* **SQL** — Business analysis and customer segmentation
* **MySQL** — Database querying
* **Power BI** — Interactive dashboards and visualization
* **Jupyter Notebook** — Analysis workflow

---

## 🔄 Project Workflow

**Raw Dataset → Data Cleaning → Exploratory Analysis → SQL Analysis → Business Insights → Power BI Dashboard → Recommendations**

### 1. Data Preparation — Python

The raw customer shopping dataset was explored and prepared for analysis.

Key tasks included:

* Inspecting data types and dataset structure
* Identifying missing and inconsistent values
* Cleaning categorical variables
* Transforming columns where required
* Creating analysis-ready features
* Performing exploratory data analysis

### 2. Data Analysis — SQL

The cleaned dataset was loaded into a relational database and analyzed using SQL.

The analysis focused on:

* Customer segmentation
* Purchase frequency
* Revenue contribution
* Product and category performance
* Customer demographics
* Subscription/loyalty behavior
* Purchase patterns

SQL techniques used include:

* `JOIN`
* `GROUP BY`
* `CASE`
* Aggregate functions
* Subqueries
* CTEs
* Window functions

### 3. Dashboard — Power BI

An interactive Power BI dashboard was created to communicate the key findings.

The dashboard includes:

* Revenue and customer KPIs
* Customer segment analysis
* Product/category performance
* Demographic analysis
* Purchase behavior
* Interactive filters and visualizations

### 4. Business Insights & Recommendations

The analysis was translated into business-focused insights rather than only presenting charts and SQL results.

The final recommendations focus on areas such as:

* Customer retention
* Customer segmentation
* Product promotion
* High-value customer targeting
* Improving customer engagement

---

## 📈 Key Insights

> Replace the points below with the **actual findings from your analysis**.

* **[Insight 1]** — Describe the most important customer or revenue finding and support it with a number.
* **[Insight 2]** — Highlight an important purchasing or product trend.
* **[Insight 3]** — Identify a meaningful difference between customer segments.
* **[Insight 4]** — Highlight a potentially actionable business opportunity.

### Example

> Customers in **[segment]** generated **X% of total revenue**, despite representing only **Y% of the customer base**, indicating an opportunity to prioritize this segment through targeted retention strategies.

---

## 📊 Power BI Dashboard

![Dashboard](images/dashboard.png)

The dashboard provides an interactive view of customer purchasing behavior, allowing users to explore the data across different customer segments, product categories, and demographic groups.

---

## 📁 Project Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## 🚀 How to Run the Project

### Python

Open the Jupyter Notebook:

```text
python/customer_behavior_analysis.ipynb
```

Run the notebook to perform data exploration, cleaning and preprocessing.

### SQL

1. Create a database in MySQL.
2. Import the cleaned dataset.
3. Execute the queries in:

```text
sql/customer_behavior_analysis.sql
```

### Power BI

Open:

```text
powerbi/customer_behavior_dashboard.pbix
```

Connect the dashboard to the prepared dataset/database if required.

---

## 💡 Business Recommendations

Based on the analysis, potential actions include:

1. **Target high-value customers** with personalized offers and retention campaigns.
2. **Focus promotional efforts** on high-performing product categories.
3. **Use customer segmentation** to create differentiated marketing strategies.
4. **Monitor purchasing behavior** to identify opportunities for increasing repeat purchases.

---

## 📌 Conclusion

This project demonstrates an end-to-end data analytics workflow, combining **Python for data preparation, SQL for business analysis, and Power BI for visualization and communication**.

The primary focus was not only on analyzing the dataset but also on translating analytical findings into **business insights and actionable recommendations**.
