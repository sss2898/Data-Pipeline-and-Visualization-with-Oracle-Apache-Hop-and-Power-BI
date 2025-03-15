# Data-Pipeline-and-Visualization-with-Oracle-Apache-Hop-and-Power-BI

This repository contains SQL scripts for setting up a data warehouse, along with an ETL pipeline implementation and Power BI reporting.

📂 Project Overview
This project involves the creation of a dimensional data warehouse with fact and dimension tables. The setup includes:

Schema creation (tables, sequences, primary keys)
ETL pipeline setup (using Apache Hop)
Data visualization (using Power BI)

📁 Files in This Repository

DimDate Create and Populate updated.txt - Creates and populates the DimDate table
DimProductCreate.txt - Creates the DimProduct table
DimCustomerCreate.txt -	Creates the DimCustomer table
FactSalesCreate.txt -	Creates the FactSales table
CustomerUpdate.csv -	CSV file containing updated customer data for ingestion
ProductUpdate.csv -	CSV file containing updated product data for ingestion
SalesUpdate.csv -	CSV file containing updated sales data for ingestion
LOAD_FACT_SALES_STAGING.hpl -	Apache Hop ETL pipeline script for loading Fact Sales Staging data
Assignment 4.pdf -	Documentation for ETL pipeline setup using Apache Hop
Assignment 5.pdf -	Documentation for Power BI Dashboard creation
