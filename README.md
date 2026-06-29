# ecom-customer-behavior-analytics
An interactive analytics dashboard visualizing key customer behavior metrics, revenue by demographic, product sales, and subscription patterns.
```markdown
# Data Analytics Project: End-to-End Customer & Sales Insights

A comprehensive, end-to-end data analytics project that covers the entire data lifecycle: from raw data ingestion and cleaning in Python, to relational database querying, interactive dashboard engineering in Power BI, and executive-level report presentation.

The project delivers actionable business intelligence regarding revenue optimization, product performance, and customer segmentation patterns.


## 📂 Project Repository Structure
* `scripts/` : Python notebooks for ETL, Data Cleaning, and EDA.
* `sql/` : SQL scripts for database schema creation and analytical queries.
* `dashboard/` : Power BI Desktop file (`.pbix`).
* `reports/` : PDF Executive Summary and documentation links.


## 📊 Project Overview
This project uncovers core business drivers by analyzing transaction histories, subscription profiles, and customer demographic segments. By engineering an end-to-end data pipeline, the project transforms messy operational tracking data into structured relational tables, uncovering insights that help optimize marketing spend, inventory allocation, and customer retention strategies.


## 🗃️ Dataset Description
The analysis is based on a comprehensive e-commerce transaction and customer profile dataset containing **3.9K unique customers**. 
* **Key Features Included:** Customer ID, Age, Gender, Purchase Amount ($), Category, Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Promo Code Used, Previous Purchases, and Payment Method.



## 🛠️ Tech Stack & Tools
* **Data Processing & EDA:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)
* **Database Management:** SQL (PostgreSQL / MySQL / SQL Server)
* **Business Intelligence:** Power BI Desktop (DAX, Power Query)
* **Presentation:** Gamma App (AI-assisted professional slide design)



## 🔄 Step-by-Step Implementation

### Step 1: Data Ingestion, Cleaning & EDA (Python)
* Identified and treated missing values and duplicate rows.
* Handled outliers and standardizing structural text formats (e.g., categories, states).
* Explored statistical summaries and distribution shapes for purchase amounts and age groups.
* Exported the clean structured dataset into a structured format for relational database loading.

### Step 2: Relational Database Querying (SQL)
* Designed a relational database schema to house the clean dataset.
* Wrote optimized SQL queries to run deep segmentations:
  * Annualized performance tracking.
  * Customer lifetime value (CLV) aggregations.
  * Windows functions (`RANK()`, `DENSE_RANK()`) to find top-selling categories per demographic.

### Step 3: BI Dashboard Engineering (Power BI)
* Imported the clean dataset/SQL views into Power BI.
* Managed data modeling by isolating categorical dim-tables from transactional fact records.
* Created calculated metrics using **DAX (Data Analysis Expressions)** (e.g., Average Purchase Value, Active Subscriptions Rate, Total Active Revenue).
* Engineered a highly interactive user UI with synchronized slicer blocks for deep-dive filtering.

### Step 4: Executive Reporting & Presentation (Gamma)
* Compiled granular metrics into a formal, structured PDF executive report.
* Handcrafted an interactive presentation deck using **Gamma App** to present high-level findings to stakeholders.



## 🎨 Dashboard Preview & Design
The interactive Power BI dashboard provides a holistic view of consumer patterns. 

### Key Visuals Included:
1. **KPI Callout Cards:** Total Customers (3.9K), Average Purchase Value ($59.76), Average Review Rating (3.75).
2. **Subscription Breakdown Donut Chart:** Highlights value difference between subscribers (27%) and non-subscribers (73%).
3. **Category Matrix Bar Charts:** Compares top revenue-generating sectors (Clothing and Accessories lead with $104K and $74K respectively).
4. **Demographic Heat Profiles:** Horizontal distribution lines plotting client acquisition scales by Age bracket (Young Adults, Middle Aged, Adults, Seniors).

*(To see the exact interface profile, see the dashboard screenshot file uploaded in the main repository).*



## 📈 Key Business Results & Insights
* **Demographic Leader:** *Young Adults* represent the single largest revenue engine, driving **$62K** in gross sales volume.
* **Core Product Focus:** *Clothing* remains the foundational business line, bringing in **$104K** across **1,737 separate sales**, significantly outperforming Outerwear and Footwear lines.
* **Subscription Runway:** Only **27%** of the user base possesses active subscriptions. Converting an additional 10% of non-subscribers represents an immediate predictable revenue growth vector.
