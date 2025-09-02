# Credit-card_Transaction_Report


## Project Overview

This repository hosts a Power BI solution designed to deliver enterprise-grade insights into credit card transactions. The dashboard aggregates transaction data, applies dynamic DAX measures, and presents key performance indicators to support data-driven decision making.

---

## Key Features

-  
  Consolidated transaction summaries by merchant category, geography, and cardholder segment  
-  
  Trend analysis of transaction volume, average spend, and delinquency rates  
-  
  Interactive slicers for date range, transaction type, and customer cohort filtering  
-  
  Custom DAX measures for month-over-month growth, rolling averages, and variance analyses  
-  
  Drill-through reports for individual cardholder and merchant transaction details  
-  
  Real-time KPI cards highlighting top merchants, highest spenders, and flagged anomalies  

---

## Technology Stack

-  
  Power BI Desktop (version 2.XX or later) for report authoring  
-  
  DAX (Data Analysis Expressions) for custom calculations  
-  
  Power Query (M language) for data ingestion and transformation  
-  
  SQL Server or Azure SQL Database as the primary data source  
-  
  Git for version control of `.pbix` files, queries, and documentation  

---

## Data Schema

| Table Name         | Description                                       |
|--------------------|---------------------------------------------------|
| Transactions       | Raw credit card transaction records (ISO 8601)    |
| Cardholders        | Customer profiles, credit limits, and demographics |
| Merchants          | Merchant identifiers, categories, and locations   |
| CurrencyRates      | Daily foreign-exchange rates for multi-currency   |

---

## Installation & Setup

1.  
   Clone the repository to your local machine:  
   ```bash
   git clone https://github.com/your-org/credit-card-pbi-dashboard.git
   ```  
2.  
   Open `CreditCardTransactionReport.pbix` in Power BI Desktop.  
3.  
   Configure the data source connection string in Power Query to point to your SQL instance.  
4.  
   Refresh the data model to load transaction, cardholder, and merchant tables.  
5.  
   Verify that DAX measures and relationships are intact, then publish to Power BI Service (optional).  

---

## Usage Instructions

-  
  Use the Date Slicer to adjust the reporting period.  
-  
  Select Cardholder segments to compare spending behaviors.  
-  
  Drill into merchant categories to identify trends and anomalies.  
-  
  Export visualizations or schedule data-driven alerts via Power BI Service.  




