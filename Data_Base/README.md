# Credit Card Performance and Customer Analysis

## Project Overview  
This project demonstrates how credit card data can be visualized using **Power BI** by connecting it directly to a **PostgreSQL** database.  
It includes two dashboards — one focusing on **customer analysis** and another on **card performance metrics**.  
The dashboards help in understanding customer demographics, transaction patterns, and credit card usage trends.

---

## Project Workflow

1. **Database Setup in PostgreSQL**
   - A database named `ccdb` was created.  
   - Two tables (`cc_detail` and `cust_detail`) were defined to store credit card and customer data.  
   - Data from `credit_card.csv` and `customer.csv` was imported using the `COPY` command in the provided SQL script.

2. **Connecting Power BI to PostgreSQL**
   - The PostgreSQL connector was used to link Power BI with the `ccdb` database.  
   - Both tables were imported and connected via the common key `Client_Num`.

3. **Data Cleaning and Modeling**
   - Data was cleaned in **Power Query Editor** (e.g., removing nulls, changing data types).  
   - Relationships were established between the two tables.  
   - DAX measures were used for calculated metrics and performance tracking.

4. **Dashboard Development in Power BI**
   - Two dashboards were designed:
     - **Customer Dashboard:** highlights customer profile, satisfaction score, and distribution by income, education, and job type.  
     - **Performance Dashboard:** visualizes transaction volumes, revenue by card type and expenditure, and delinquency distribution.  
   - Visuals include bar charts, pie charts, KPIs, and filters for interactivity.

5. **Export and Sharing**
   - Dashboards were formatted for professional presentation and exported as PDF files for sharing and documentation.

---

## Tools & Technologies Used
- **Database:** PostgreSQL  
- **Data Source:** CSV files  
- **Visualization:** Power BI Desktop  
- **Languages:** SQL, DAX  

---

## Summary
This project highlights an end-to-end process of integrating **PostgreSQL** with **Power BI** to build dynamic dashboards.  
It demonstrates how raw CSV data can be transformed into meaningful business insights through SQL queries, data modeling, and interactive visualization.

---
