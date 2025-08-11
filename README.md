# Nawab-motors (SQL + PowerBI)


------------------------------------------------------------------------------------Car Sales Dashboard Project------------------------------------------------------------------------------------------------------

# Overview
This project showcases a complete data analytics workflow—from raw Excel files to an interactive Power BI dashboard. The goal is to provide insights into car sales, ownership trends, insurance coverage, and service history using SQL and Power BI.


# Data Sources
The analysis is based on multiple Excel files:
- car_data.csv – Primary reference table containing car details
- insurance_data.csv – Insurance coverage information
- sales_data.csv – Sales transactions
- service_history.csv – Maintenance and service records
- owners_data.csv – Owner demographics and history


# Data Preparation (SQL)
I use LEFT JOINs for all supporting tables because car_table serves as the primary reference table. This ensures that:
- Every record from car_table is retained in the final dataset.
- Related data from other tables (e.g., sales, customer, region) is included only if a matching car_id exists.
- Missing values from non-matching rows are handled gracefully, preserving the integrity of the main car dataset.
This approach guarantees a comprehensive view of all cars, even if some have no associated sales or customer data.


# Dashboard Development (Power BI)
The master_table was loaded into Power BI to create an interactive dashboard featuring:
-  Sales trends by car model and region
-  Ownership demographics
-  Insurance coverage analysis
-  Service frequency and history
-  Filters and slicers for dynamic exploration


# Key Features
- Clean and structured SQL joins using LEFT JOIN logic
- Data transformation and aggregation for dashboard KPIs
- Visual storytelling through Power BI charts and slicers
- Designed for clarity, interactivity, and business insight
📁 Folder Structure
├── SQL_Scripts/
│   └── master_table_creation.sql
├── PowerBI_Dashboard/
│   └── Car_Sales_Dashboard.pbix
├── Data/
│   ├── car_data.csv
│   ├── insurance_data.csv
│   ├── sales_data.csv
│   ├── service_history.csv
│   └── owners_data.csv
└── README.md


#Learnings & Highlights
- Mastered SQL joins and data cleaning techniques
- Built a multi-layered Power BI dashboard with storytelling elements
- Practiced real-world data integration and visualization


