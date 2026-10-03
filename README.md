# 🛒 E‑Commerce Sales & Customer Analysis

<div align="center">

<img src="https://img.shields.io/badge/Python-Data%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Cleaning-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-Numerical%20Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Seaborn-Main%20Visualization-4C72B0?style=for-the-badge"/>

📊 Explore • 🔎 Analyze • 🎨 Visualize • 💡 Understand

</div>

---

## 🎯 Overview

A complete **exploratory data analysis and visualization project** built using the **UCI Online Retail Dataset**.

The goal is to understand **sales, products, customers, countries, transaction patterns**, and **numerical relationships** using Python — with a special focus on **Seaborn** for visualization.

**Workflow:**  
Raw Data → Cleaning → Feature Engineering → EDA → Seaborn Visualization → Business Insights

---

## 💡 Business Questions

| Area | Question |
|------|-----------|
| 🏆 Products | Which products generate the highest revenue? |
| 📦 Quantity | Which products have the highest quantity sold? |
| 🌍 Countries | Which countries generate the most revenue? |
| 💰 Revenue | How is transaction revenue distributed? |
| 🧾 Transactions | Which countries have the most transaction records? |
| 🔗 Relationships | Is there a relationship between quantity and unit price? |
| 📊 Distribution | How does revenue distribution differ between countries? |
| 🔥 Correlation | Which numerical variables are related? |

---

## 🧠 Project Workflow
RAW DATA → DATA CLEANING → FEATURE ENGINEERING → EDA → SEABORN VISUALIZATION → INSIGHTS → CONCLUSION

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| 🐍 Python | Core programming |
| 🐼 Pandas | Data cleaning and manipulation |
| 🔢 NumPy | Numerical operations |
| 📈 Matplotlib | Plot control and customization |
| 🎨 Seaborn | Main statistical visualization |
| 📦 ucimlrepo | Dataset retrieval |
| 📓 Jupyter Notebook | Analysis environment |

---

## 🎨 Seaborn Visualization Journey

### 📈 Distribution Analysis
`histplot()` → `kdeplot()` → `boxplot()` → `violinplot()` → `displot()`  
Understand revenue distribution, spread, density, and outliers.

### 📊 Categorical Analysis
`barplot()` → `countplot()` → `pointplot()` → `catplot()`  
Compare products, countries, transaction counts, and averages.

### 🔗 Relationship Analysis
`scatterplot()` → `regplot()` → `pairplot()`  
Study relationships, trends, and multiple numerical variables.

### 🧩 Advanced Visualization
`heatmap()` → `FacetGrid()`  
Perform correlation analysis and group-based visual comparison.

---

## 🗂️ Dataset

**Source:** UCI Online Retail Dataset  
**Key Columns:** Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

**Revenue Formula:**  


\[
\text{Revenue} = \text{Quantity} \times \text{UnitPrice}
\]



---

## 🧹 Data Preparation Steps

- Remove duplicates  
- Handle missing values  
- Convert `InvoiceDate` to datetime  
- Create `Revenue` feature  
- Extract `Year`, `Month`, `Day`, `Hour`  
- Create `YearMonth`  
- Prepare data for visualization  

---

## 📊 KPI Analysis

| Metric | Description |
|---------|--------------|
| 💰 Total Revenue | Overall monetary value |
| 📦 Total Quantity | Total items sold |
| 🧾 Total Transactions | Number of invoices |
| 🛍️ Total Products | Unique product count |
| 👥 Total Customers | Unique customer count |
| 🌍 Total Countries | Number of countries |

---

## 🔍 Visualization Approach

Each visualization answers a specific business question:

Business Question → Choose Plot → Create Visualization → Find Pattern → Interpret → Insight


**Example: Revenue Distribution**  
→ `histplot()` / `kdeplot()` → Understand spread → Identify concentration & outliers  

**Example: Quantity vs Unit Price**  
→ `scatterplot()` / `regplot()` → Observe relationship & trend  

**Example: Correlation**  
→ `heatmap()` → Compare correlation values  

---

## 📁 Project Structure

ecommerce-sales-customer-analysis/
│
├── 📓 ecommerce_sales_customer_analysis.ipynb
├── 📄 README.md
├── 📦 requirements.txt
└── 🚫 .gitignore



---

## ⚡ Getting Started

bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/ecommerce-sales-customer-analysis.git
cd ecommerce-sales-customer-analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

📦 Requirements
pandas
numpy
matplotlib
seaborn
ucimlrepo
jupyter

💡 What I Learned
Python for data analysis

Pandas for cleaning

NumPy for numerical operations

Matplotlib for visualization

Seaborn for statistical plots

Exploratory Data Analysis (EDA)

Correlation and categorical comparison

Business‑oriented interpretation

Main takeaway: choosing the right visualization for each analytical question.


🧭** Learning Progress **
PYTHON
  ↓
Pandas + NumPy + Matplotlib
  ↓
DATA ANALYSIS
  ↓
SEABORN
  ↓
Distribution • Categories • Relationships
  ↓
BUSINESS INSIGHTS


👨‍💻 Author
<div align="center">

Savan Sojitra  
B.Tech Computer Science Student
Python • Data Analysis • Visualization • AI Engineering

<a href="https://github.com/YOUR-USERNAME">
<img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

📊 DATA → 🔎 ANALYSIS → 🎨 VISUALIZATION → 💡 INSIGHT

Built with Python, Pandas, NumPy, Matplotlib & Seaborn

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=120&section=footer"/>
</div>


