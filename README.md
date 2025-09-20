[README.md](https://github.com/user-attachments/files/22438757/README.md)
# 🧾 Walmart Sales Key Performance Indicator - Python+Sql

![Project Pipeline](https://github.com/iamitdaslive/walmart_sales_kpi_python_sql/blob/main/images/walmart_project_workflow.png)


_An end-to-end **Walmart sales analysis project** using **Python (Pandas, SQLAlchemy)** and **SQL (PostgreSQL)**.  
The project focuses on **data cleaning, feature engineering, SQL-based KPI analysis, and business insights** to help optimize Walmart’s sales performance._

---

## 📌 Table of Contents
- <a href="#introduction">Introduction</a>
- <a href="#overview">Overview</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#steps">Steps</a>
- <a href="#requirements">Requirements</a>
- <a href="#results--insights">Results & Insights</a>
- <a href="#future-scope">Future Scope</a>
- <a href="#author--contact">Author & Contact</a>


---
<h2><a class="anchor" id="introduction"></a>Introduction</h2>

Retail giants like Walmart rely heavily on **data-driven insights** to improve revenue, optimize operations, and understand customer behavior.  
This project applies **Python and SQL** to extract, clean, and analyze sales data from Walmart, focusing on **KPIs such as revenue, profit margins, customer preferences, and branch performance**.

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

- Cleaned and prepared raw sales data.  
- Engineered new KPIs (e.g., Total Amount per transaction, gross profit).  
- Loaded processed data into **MySQL & PostgreSQL** databases.  
- Ran **complex SQL queries** to answer business problems.  
- Documented results for better **business decision-making**.  


---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- **Records**: ~10,000 transactions  
- **Key Features**:
  - `Invoice ID`, `Branch`, `City`, `Customer Type`, `Gender`  
  - `Product Line`, `Unit Price`, `Quantity`, `Total`, `Tax`, `COGS`  
  - `Date`, `Time`, `Payment Method`, `Rating`  

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- **Languages**: Python, SQL (MySQL, PostgreSQL)  
- **Libraries**: `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`, `psycopg2`  
- **Environment**: Jupyter Notebook, VS Code  
- **Data Source**: Kaggle API  

---
---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
Walmart Sales Kpi Python Sql/
│
├── cleaned_data/ #  clean dataset
│ └── Store_cleaned_data.csv
│
├── kpi_walmart_psql.sql/ # SQL queries for analysis
│ 
├── src/ # Python code in jupyter nootebook 
│ └── project_walmart_python.ipynb
├── images
│ └── walmart_project_workflow.png
│
├── raw_datasets
│ └── Walmart.csv
│
├── reports/ # Business Q&A Report
│ └── report_walmart_kpi.pdf
│
│
├── document_business_problems.pdf
│
├── requirements.text
│
└── README.md # Project overview
```

---
<h2><a class="anchor" id="steps"></a>Steps</h2>

### 1. Set Up the Environment
- **Tools Used**: VS Code, Python, MySQL, PostgreSQL  
- **Goal**: Create a structured workspace with organized folders.

---

### 2. Set Up Kaggle API
- Download your Kaggle API token from [Kaggle](https://www.kaggle.com/).  
- Place `kaggle.json` in your local `.kaggle/` folder.  
- Run:
  ```bash
  kaggle datasets download -d najir0123/walmart-10k-sales-datasets
---
### 3. Download Walmart Sales Data
- Save dataset inside the `data/` folder.

---

### 4. Install Required Libraries & Load Data

  ```bash
  pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
```
- Load CSV into a Pandas DataFrame.

---

### 5. Explore the Data

* Use `.head()`, `.info()`, `.describe()` to understand structure.  

---

### 6. Data Cleaning
* Remove duplicates & missing values.  
* Convert dates and times to proper `datetime`.  
* Format currency values.  
* Validate cleaned dataset.  

---

### 7. Feature Engineering
* Create `Total Amount = Unit Price × Quantity`.  
* Add derived KPIs for revenue and profit.  

---

### 8. Load Data into SQL Databases
* Connect Python → MySQL & PostgreSQL using `sqlalchemy`.  
* Create tables and insert cleaned dataset.  

---

### 9. SQL Analysis & Business Problem Solving
* **Revenue trends across branches & categories**.  
* **Best-selling product categories**.  
* **Peak sales periods & customer behavior**.  
* **Profit margins per branch and category**.  

---

### 10. Project Publishing
* Push repo to GitHub including:  
  * `README.md`  
  * SQL scripts  
  * Jupyter Notebook  
  * Documentation reports  




---
<h2><a class="anchor" id="requirements"></a>Requirements</h2>

- **Python 3.8+**  
- **SQL Databases**: MySQL, PostgreSQL  
* **Libraries**:  
  * pandas  
  * numpy  
  * sqlalchemy  
  * mysql-connector-python  
  * psycopg2  
* **Kaggle API Key**  
---

<h2><a class="anchor" id="results--insights"></a>Results & Insights</h2>

## 📊 Results & Insights

* **Revenue Insights**  
  - Branches with the highest revenue.  
  - Seasonal revenue fluctuations.  

* **Customer Behavior**  
  - Identified peak shopping hours.  
  - Segmentation by customer type (e.g., members vs. non-members).  

* **Profitability**  
  - Most profitable product lines.  
  - Branch-level profitability comparison.  

* **Business Problem Solved**  
  - Provided data-driven insights into customer behavior and branch performance.  
  - Helped identify areas for **cost optimization** and **revenue growth**.  

---
<h2><a class="anchor" id="future-scope"></a>Future Scope</h2>

## 🔮 Future Scope

* Add **real-time streaming data pipelines**.  
* Implement **predictive analytics (ML models)** for forecasting demand.  
* Build an **interactive Power BI dashboard**.  
* Automate **ETL workflows** for continuous updates.  
* Integrate **customer feedback sentiment analysis**.  


---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Amit Das**  
Data Analyst  
📧 Email: amit18das32@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/amit-das-0bb800158)  
