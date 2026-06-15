# Data Analytics Project: Customer Shopping Behavior Analysis

## Overview

This project demonstrates an end-to-end Data Analytics workflow using Python, SQL, Power BI, and reporting tools. The objective is to analyze customer shopping behavior, uncover business insights, and present findings through interactive dashboards and professional reports.

The project covers data loading, data cleaning, exploratory data analysis (EDA), SQL-based analysis, dashboard development, and presentation creation.

---

## Dataset

**Dataset Name:** Customer Shopping Behavior Dataset

### Dataset Features

* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount (USD)
* Location
* Size
* Color
* Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied
* Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Database

* PostgreSQL
* MySQL
* SQL Server

### Visualization

* Power BI

### Reporting & Presentation

* Microsoft PowerPoint
* Gamma AI

### Development Environment

* Jupyter Notebook
* VS Code

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Pandas.
* Verified data structure and data types.
* Performed initial inspection of records.

### 2. Data Cleaning

* Checked missing values.
* Removed duplicate records.
* Corrected data types.
* Standardized column names.
* Validated data consistency.

### 3. Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Customer demographics
* Purchase trends
* Revenue distribution
* Product category performance
* Subscription behavior
* Shipping preferences
* Discount impact on purchases

Visualizations created:

* Bar Charts
* Histograms
* Pie Charts
* Count Plots
* Correlation Analysis

### 4. SQL Analysis

Loaded the cleaned dataset into PostgreSQL/MySQL/SQL Server and executed analytical queries such as:

* Revenue by category
* Revenue by gender
* Subscription-based spending analysis
* Top-selling products
* Customer segmentation
* Discount effectiveness
* Shipping type comparison
* Repeat customer analysis
* Purchase frequency analysis

### 5. Power BI Dashboard

Built an interactive dashboard containing:

#### KPI Cards

* Total Revenue
* Total Customers
* Average Purchase Value
* Total Orders

#### Visualizations

* Revenue by Category
* Revenue by Gender
* Revenue by Location
* Subscription Status Analysis
* Shipping Type Analysis
* Discount Analysis
* Top Purchased Products

#### Dashboard Features

* Interactive Filters
* Dynamic Visuals
* Drill-Down Analysis
* Business KPI Monitoring

### 6. Reporting

Created a business report summarizing:

* Key findings
* Customer behavior insights
* Revenue trends
* Product performance
* Recommendations

### 7. Presentation

Designed a professional presentation using Gamma AI including:

* Project Overview
* Methodology
* Key Insights
* Dashboard Screenshots
* Business Recommendations
* Conclusion

---

## Key Results

### Business Insights

* Identified top-performing product categories.
* Measured the impact of discounts on sales.
* Compared spending behavior across customer segments.
* Analyzed subscription-based customer performance.
* Evaluated shipping preferences and purchasing patterns.

### Outcomes

* Improved understanding of customer behavior.
* Generated actionable business recommendations.
* Delivered an interactive decision-support dashboard.

---

## Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── PowerBI_Dashboard.pbix
│
├── reports/
│   └── Project_Report.pdf
│
├── presentation/
│   └── Gamma_Presentation.pptx
│
└── README.md
```

---

## How to Run

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/data-analytics-project.git
cd data-analytics-project
```

### Step 2: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### Step 3: Run EDA Notebook

```bash
jupyter notebook
```

Open and execute:

```text
EDA.ipynb
```

### Step 4: Load Data into Database

Configure database connection settings and run the data loading script.

### Step 5: Execute SQL Queries

Run queries in:

* PostgreSQL
* MySQL
* SQL Server

### Step 6: Open Power BI Dashboard

Open:

```text
PowerBI_Dashboard.pbix
```

### Step 7: Review Report & Presentation

* Project_Report.pdf
* Gamma_Presentation.pptx

---

## Author

**Anshul Yadav**

Data Analytics | SQL | Python | Power BI | Machine Learning

---

## Future Improvements

* Predictive Analytics using Machine Learning
* Customer Segmentation using Clustering
* Sales Forecasting
* Real-Time Dashboard Integration
* Automated Reporting Pipeline

