# 🛍️ Customer Behavior Analytics Project

## 📝 Overview
This end-to-end data analytics project provides a deep-dive look into customer shopping behavior to uncover high-value insights, optimize marketing strategies, and track purchasing trends. The project spans the entire data lifecycle: from building ingestion pipelines and conducting detailed exploratory data analysis (EDA) in Python, to advanced relational modeling and querying in SQL, and finally to deploying an executive-level interactive dashboard in Power BI. 

---

## 📊 Dataset Architecture
The primary dataset consists of transactional logs and rich customer demographic profiles. The structure includes the following core attributes:

*   **🆔 Customer ID:** Unique alphanumeric identifier for tracking individual shopping lifecycles.
*   **👥 Demographics:** Granular breakdown of customer profiles including *Age*, *Gender*, and *Geographic Location*.
*   **💰 Purchase Details:** Financial metrics including *Item Purchased*, *Product Category*, *Purchase Amount (USD)*, and *Shipping Type*.
*   **🔄 Behavioral Metrics:** Frequency-of-purchase indicators, historical retention metrics, and system-generated *Customer Segments*.
*   **🎫 Promotion Tracking:** Evaluation of *Discounts Applied*, *Promo Codes Used*, and *Subscription Status*.

---

## 🛠️ Tech Stack & Tooling

| Technology | Purpose | Key Libraries / Features |
| :--- | :--- | :--- |
| **🐍 Python** | Data Wrangling & EDA | Pandas, NumPy, Matplotlib, Seaborn |
| **🛢️ SQL** | Database Ingestion & Business Logic | PostgreSQL / MySQL / SQL Server |
| **📊 Power BI** | Interactive Visualizations & Reporting | DAX, Power Query, Star Schema Modeling |


---

## 🚀 Step-by-Step Implementation Pipeline

### 1. 🧹 Data Cleaning & Exploratory Data Analysis (Python)
*   **Missing Value Imputation:** Identified and systematically resolved null values and data anomalies without skewing population metrics.
*   **Feature Engineering:** Standardized categorical values and binned continuous numerical features (e.g., grouping age into logical generations like *Gen Z, Millennials, Gen X*).
*   **Statistical Analysis:** Conducted distribution analysis on key purchasing metrics and built correlation matrices using Seaborn to map the impact of active subscription statuses on average order value (AOV).
*   **Pipeline Export:** Generated a highly optimized, fully structured target `.csv` file prepared for seamless relational database migration.

### 2. 💾 Relational Database Management & Query Optimization (SQL)
*   **Schema Design:** Formulated clean DDL scripts to establish primary keys, strict data types, and logical constraints.
*   **Analytical Queries:** Authored highly optimized SQL scripts using Window Functions (`RANK()`, `ROW_NUMBER()`), Complex CTEs, and Aggregate Functions to answer high-stakes business requirements.
*   **Performance Metrics Targeted:**
    *   Total revenue trends across distinct product categories.
    *   Average spend patterns segmented by customer loyalty levels.
    *   Cohort distribution patterns across key geographic sectors.

### 3. 🎨 Business Intelligence & UI/UX Dashboarding (Power BI)
*   **Data Modeling:** Established a streamlined data model utilizing optimized relationships inside Power BI.
*   **DAX Architecture:** Formulated complex DAX measures for core business KPIs including *Year-over-Year Growth*, *Total Dynamic Revenue*, and *Moving Averages*.
*   **UI/UX Formatting:** Applied corporate design guidelines with unified color palettes, clean spacing, and intuitive navigation bookmarks to ensure recruiter-friendly scannability.

---

## 🖥️ Interactive Dashboard Preview
<img width="1289" height="709" alt="chun" src="https://github.com/user-attachments/assets/6284040a-4c65-467c-a002-8b21f15ab445" />


---

## 💡 Key Business Insights Discovered
*   **🥇 Revenue Engines:** Specific product categories contributed disproportionately to the total revenue pool, signaling clear targets for inventory expansion.
*   **🎯 Target Audiences:** Identified the core age demographic and gender profiles responsible for the highest purchase frequency rates.
*   **📈 Retention Mechanics:** Loyalty program members and discount strategies demonstrated a statistically valid lift in long-term customer lifetime value (LTV).

---

## ⚙️ How to Deploy & Execute This Project

### 📋 Prerequisites
Ensure you have the following environments configured on your local machine:
*   Python 3.10+ (Anaconda or Jupyter Environment recommended)
*   Relational Database Instance (PostgreSQL / MySQL / SQL Server)
*   Power BI Desktop (Latest Version)

### 💻 Local Setup Instructions
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/customer-behavior-analysis.git](https://github.com/your-username/customer-behavior-analysis.git)
    ```
2.  **Run the Python Pipeline:** Open `Customer_Shopping_Behavior_Analysis.ipynb` inside your Jupyter environment and run all cells to generate the clean output datasets.
3.  **Initialize the Database Schema:** Execute the queries found inside `customer_behavior_sql_queries.sql` within your SQL editor to instantly seed your tables.
4.  **Launch the Interactive Report:** Double-click on `customer_behavior_dashboard.pbix` to explore the metrics live via Power BI Desktop.
