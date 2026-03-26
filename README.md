# 📊 Data Analytics Portfolio – Excel Foundations Project

## 🚀 Overview
This project showcases my foundational data analysis skills developed during a **Data Technician Bootcamp**, where I worked with retail and sales datasets to extract insights, build summaries, and apply analytical logic using Excel.

The focus of this project is not just technical execution, but demonstrating how **data can be transformed into meaningful business insights**.

---

## 🧠 Key Skills Demonstrated

### 📌 Data Manipulation & Cleaning
- Filtering datasets to identify key segments (e.g. sorting age demographics)
- Structuring raw datasets for analysis
- Preparing data for aggregation and reporting

### 📊 Excel Functions & Formulas
- `SUM` → Aggregating totals (e.g. commission)
- `AVERAGE` → Identifying performance trends  
- `SWITCH` → Creating dynamic classification logic  
- Logical conditions for categorisation (High / Medium / Low)
<img width="80" height="340" alt="image" src="https://github.com/user-attachments/assets/57e84e4e-50e2-48e2-9d5e-9817bc634798" />


### 📈 Data Analysis Techniques
- Analysing patterns across:
  - Age groups  
  - Gender segments  
  - Geographic regions  
- Comparing performance metrics across multiple variables  
- Extracting insights from aggregated datasets  

### 📉 Pivot Tables & Data Modelling
- Built Pivot Tables to:
  - Summarise sales by product type, age group, and gender**
  - Analyse **product performance by each deomgraphic
- Structured datasets for multi-dimensional analysis
  <img width="800" height="340" alt="image" src="https://github.com/user-attachments/assets/679e3e6b-d3a5-4b3b-8d73-2b5a91ef9002" />
 

---

## 🔍 Project Highlights

### 1. Sales & Commission Analysis
- Calculated total and average commission values  
- Identified distribution trends across datasets  

**Example outcomes:**
- Total commission calculated using aggregation techniques  
- Average commission used to evaluate performance benchmarks  

---

### 2. Customer Segmentation Analysis
- Analysed customer demographics across:
  - Countries
  - Age groups
  - Gender  

**Key insights:**
- Adult customers represent the **highest purchasing segment**
- Female customers show **strong purchasing frequency across all age groups**
- Markets such as the **UK and Australia have full demographic coverage**

---

### 3. Market & Product Performance (Pivot Table Project)
- Built a Pivot Table to analyse:
  - Sales volume by **county and product**

- Applied classification logic using `SWITCH`:

```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
