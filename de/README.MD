# Data Engineering Exercise

We greatly value your time, so please focus on demonstrating your approach rather than perfecting every detail.  

## Task Overview

### 1. Customer-Oriented Sales Table (ETL)
- Build an ETL pipeline that produces a **customer-oriented sales table** from raw transactional sales data. [Iowa Liquor Sales Dataset](https://console.cloud.google.com/marketplace/details/iowa-department-of-commerce/iowa-liquor-sales).  
- Transform the raw data into a table designed for **downstream data science and forecasting tasks**.  
  - Example: aggregate at **weekly customer–product** level with metrics such as `total_sales`, `total_units`, and other useful features.  
- Clearly document your assumptions about the raw schema and transformation logic.  

---

### 2. Holiday Table Data Pipeline
- Create a pipeline to generate a **holiday/calendar reference table**.  
- Data sources may include:
  - Python packages (e.g., `holidays`, `workalendar`)
  - Public APIs
  - Web scraping of official sources or 3rd party websites
- The table should cover **the current and next calendar year**.  
- Ensure coverage across **ONE’s operating countries** (you can find the information from ONE website) — the broader the coverage, the better.  
- The final table should at minimum include:
  - `country`
  - `holiday_date`
  - `holiday_name`
  - `is_public_holiday` (boolean)

---

## Requirements
- Document and explain any assumptions, decisions, or shortcuts (e.g., due to time constraints).  
- You are free to choose your tools and format, but your documentation should clearly explain your process and reasoning.  
- Use Python and any other tools you are comfortable with for ETL and pipeline development.  
- Share your code and documents with github account jintao-li-one or mail jintao.li@one-line.com using a version control system of your choice (GitHub etc.) and restrict public access.
