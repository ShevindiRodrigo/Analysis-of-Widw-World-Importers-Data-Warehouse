# 🌐 World Wide Importers BI & Data Mart Project

## 📁 Project Overview
This project presents a Business Intelligence (BI) and Data Mart solution built using Microsoft SQL Server, SSIS, SSAS, Power BI, and Excel. The aim is to provide actionable insights into the sales performance, delivery logistics, and inventory management of Wide World Importers (WWI), a wholesale novelty goods distributor.

The project focuses on two core analytical areas:
- **Sales Performance Analysis**
- **Logistics and Stock Movement Monitoring**

## 📊 Objectives
- Design data marts for sales and logistics.
- Create OLAP cubes using SQL Server Analysis Services (SSAS).
- Build and deploy ETL pipelines with SQL Server Integration Services (SSIS).
- Generate dashboards and reports using Power BI and Excel.
- Deliver clear, executive-level insights to guide business decisions.

## 🧰 Tools & Technologies
- **SQL Server 2019** – Database engine
- **SSIS** – ETL pipelines for data extraction and transformation
- **SSAS (Multidimensional)** – Cube design and data modeling
- **Power BI** – Data visualisation and dashboarding
- **Excel** – Additional data analysis
- **Jupyter Notebooks (Python)** – Supplemental exploratory analysis
- **Git** – Version control for documentation and report assets

## 🧱 Data Sources
The project uses the sample **WideWorldImportersDW** database provided by Microsoft:
- Download Link: [WWI Data Warehouse Sample](https://github.com/Microsoft/sql-server-samples/releases/tag/wide-world-importers-v1.0)
- Key Fact Tables: `Fact.Sale`, `Fact.Order`, `Fact.Movement`, `Fact.StockHolding`
- Key Dimension Tables: `Dim.Customer`, `Dim.City`, `Dim.Employee`, `Dim.StockItem`, `Dim.Date`


## 📈 Key Features
### Sales Analysis
- Yearly and monthly sales trends (2013–2016)
- Top-selling products and top-performing salespeople
- Regional performance across US states
- Customer segmentation and category breakdown

### Logistics Monitoring
- Delivery performance (average delivery times)
- High-movement stock items and seasonal stock flow
- Stock in/out trends by product and time
- Dashboard to track warehouse activity and distribution

## 🔍 Insights Delivered
- Identified a **drop in total sales and orders in 2016**, prompting need for strategic review.
- Found that **Q4 accounts for over 35% of revenue**, guiding seasonal marketing efforts.
- Determined that **20% of products contribute to 70% of profit**, enabling inventory prioritisation.
- Mapped **delivery efficiency** with average delivery time at just **1 day**.

## 🎯 Outcomes
- Improved executive visibility into KPIs
- Enhanced decision-making for stock management
- Actionable recommendations for sales strategy and market expansion
- Demonstrated ability to design and deliver end-to-end BI solutions

## 📽️ Presentation
A professional 3-minute presentation was delivered, highlighting:
- BI workflow
- Dashboard demos
- Key findings and business recommendations

## 📄 Author
**Shevindi Rodrigo**  
📍 Newcastle, NSW, Australia  
📧 shevi.rodrigo@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/shevindirodrigo)  
🔗 [Portfolio](https://shevindirodrigo.github.io)

---

> 📌 *This project was developed as part of INFO6002 – Database Management 2 (University of Newcastle, 2024)*
