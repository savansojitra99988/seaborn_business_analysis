<div align="center">



<img src="https://img.shields.io/badge/Python-Data%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Cleaning-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-Numerical%20Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Seaborn-Main%20Visualization-4C72B0?style=for-the-badge"/>

📊 Explore • 🔎 Analyze • 🎨 Visualize • 💡 Understand

</div>

🛒 E-Commerce Sales & Customer Analysis

A complete exploratory data analysis and visualization project built using the UCI Online Retail Dataset.

The main goal of this project is to understand e-commerce sales, products, customers, countries, transaction patterns and numerical relationships using Python.

The project places special focus on Seaborn, covering visualization techniques from basic to advanced.

Raw Data → Cleaning → Feature Engineering → EDA → Seaborn Visualization → Business Insights

🎯 Business Questions

Area

Question

🏆 Products

Which products generate the highest revenue?

📦 Quantity

Which products have the highest quantity sold?

🌍 Countries

Which countries generate the most revenue?

💰 Revenue

How is transaction revenue distributed?

🧾 Transactions

Which countries have the most transaction records?

🔗 Relationships

Is there a relationship between quantity and unit price?

📊 Distribution

How does revenue distribution differ between countries?

🔥 Correlation

Which numerical variables are related?

🧠 Project Workflow

                    ┌───────────────┐
                    │   RAW DATA    │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │ DATA CLEANING  │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │    FEATURE    │
                    │  ENGINEERING  │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │     EDA       │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │   SEABORN     │
                    │ VISUALIZATION │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │   INSIGHTS    │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │  CONCLUSION   │
                    └───────────────┘

🛠️ Tech Stack

Technology

Purpose

🐍 Python

Core programming

🐼 Pandas

Data cleaning and manipulation

🔢 NumPy

Numerical operations

📈 Matplotlib

Plot control and customization

🎨 Seaborn

Main statistical visualization

📦 ucimlrepo

Dataset retrieval

📓 Jupyter Notebook

Analysis environment

🎨 Seaborn Visualization Journey

The project uses different Seaborn functions for different analytical questions.

📈 Distribution Analysis

histplot() → kdeplot() → boxplot() → violinplot() → displot()

Used to understand revenue distribution, spread, density and outliers.

📊 Categorical Analysis

barplot() → countplot() → pointplot() → catplot()

Used to compare products, countries, transaction counts and average values.

🔗 Relationship Analysis

scatterplot() → regplot() → pairplot()

Used to study relationships, trends and multiple numerical variables.

🧩 Advanced Visualization

heatmap() → FacetGrid

Used for correlation analysis and group-based visual comparison.

📚 Seaborn Functions Covered

Function

Purpose

histplot()

Revenue and quantity distribution

kdeplot()

Smooth distribution

boxplot()

Spread and outlier detection

violinplot()

Distribution across categories

barplot()

Category comparison

countplot()

Transaction counts

scatterplot()

Numerical relationships

regplot()

Relationship with trend

pointplot()

Average values

catplot()

Categorical comparisons

pairplot()

Multiple numerical relationships

heatmap()

Correlation matrix

FacetGrid

Group-based comparison

displot()

Figure-level distribution

🗂️ Dataset

UCI Online Retail Dataset

The project uses transaction data from an online retail store.

Important Columns

Description
Quantity
InvoiceDate
UnitPrice
CustomerID
Country

💰 Revenue Feature

Revenue is calculated as:

Revenue = Quantity × UnitPrice

This feature is used to analyze the monetary value of transactions.

🧹 Data Preparation

The notebook performs the main preparation steps required for analysis:

Remove duplicate records

Handle missing values

Convert InvoiceDate to datetime

Create Revenue

Extract Year

Extract Month

Extract Day

Extract Hour

Create YearMonth

Prepare data for visualization

📊 KPI Analysis

The project calculates important business metrics:

💰 Total Revenue
📦 Total Quantity
🧾 Total Transactions
🛍️ Total Products
👥 Total Customers
🌍 Total Countries

These KPIs provide a quick overview before deeper analysis.

🔍 Visualization Approach

Each visualization is connected to a specific analytical question.

Business Question
       ↓
Choose Suitable Plot
       ↓
Create Visualization
       ↓
Find Pattern
       ↓
Interpret Result
       ↓
Business Insight

Example — Revenue Distribution

Question:
How are transaction revenues distributed?

        ↓

histplot() / kdeplot()

        ↓

Understand distribution

        ↓

Identify concentration and outliers

Example — Quantity vs Unit Price

Question:
Is there a relationship between quantity and price?

        ↓

scatterplot()

        ↓

regplot()

        ↓

Observe relationship and trend

Example — Correlation

Question:
Which numerical variables are related?

        ↓

heatmap()

        ↓

Compare correlation values

📁 Project Structure

ecommerce-sales-customer-analysis/
│
├── 📓 ecommerce_sales_customer_analysis.ipynb
├── 📄 README.md
├── 📦 requirements.txt
└── 🚫 .gitignore

⚡ Getting Started

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/ecommerce-sales-customer-analysis.git
cd ecommerce-sales-customer-analysis

2. Install dependencies

pip install -r requirements.txt

3. Start Jupyter Notebook

jupyter notebook

Open:

ecommerce_sales_customer_analysis.ipynb

The notebook retrieves the UCI dataset using ucimlrepo.

📦 Requirements

pandas
numpy
matplotlib
seaborn
ucimlrepo
jupyter

💡 What I Learned

Through this project, I practiced:

🐍 Python for data analysis

🐼 Pandas data cleaning

🔢 NumPy numerical operations

📈 Matplotlib visualization

🎨 Seaborn statistical visualization

📊 Exploratory Data Analysis

🔗 Correlation analysis

🌍 Categorical comparison

🧩 Multi-variable visualization

💼 Business-oriented data interpretation

📓 Building a complete data analysis workflow

The main learning outcome was understanding which visualization to choose for a particular analytical question.

🧭 Learning Progress

                         PYTHON
                            │
             ┌──────────────┼──────────────┐
             ↓              ↓              ↓
          Pandas          NumPy        Matplotlib
             └──────────────┼──────────────┘
                            ↓
                     DATA ANALYSIS
                            ↓
                         SEABORN
                            │
          ┌─────────────────┼─────────────────┐
          ↓                 ↓                 ↓
    Distribution       Categories       Relationships
          └─────────────────┼─────────────────┘
                            ↓
                    BUSINESS INSIGHTS

🚀 Future Improvements

Customer Segmentation

RFM Analysis

Customer Lifetime Value

Advanced Statistical Analysis

Interactive Dashboard

Advanced Seaborn Styling

Machine Learning for Customer Behavior

👨‍💻 Author

<div align="center">

Savan Sojitra

B.Tech Computer Science Student

Python • Data Analysis • Visualization • AI Engineering

<a href="https://github.com/YOUR-USERNAME">
<img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br><br>

📊 DATA → 🔎 ANALYSIS → 🎨 VISUALIZATION → 💡 INSIGHT

Built with Python, Pandas, NumPy, Matplotlib & Seaborn

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=120&section=footer"/>

</div>
