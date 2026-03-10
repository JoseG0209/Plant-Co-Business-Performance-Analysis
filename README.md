# Plant Co Business Performance Analysis

Power BI dashboard focused on analyzing business performance using key metrics such as Gross Profit, Sales, and Quantity.

## Overview
This project analyzes Plant Co. performance between **2022 and 2024** using an interactive Power BI dashboard.

The report allows users to dynamically switch between different business metrics and evaluate performance across time, countries, and products.

## Metrics Analyzed
- Gross Profit
- Sales
- Quantity
- YTD
- PYTD
- YTD vs PYTD
- GP%

## Features
- Dynamic metric selector (Gross Profit, Sales, Quantity)
- Year filtering
- Time intelligence analysis (YTD vs PYTD)
- Country performance comparison
- Product-level insights
- Monthly performance trends

## Data Model
The dashboard follows a **star schema model** including:

- Fact_Sales
- Dim_Date
- Dim_Product
- Dim_Account
- Slc_Values
- _Measures

Custom DAX measures were used to calculate KPIs and enable dynamic metric switching.

## Tools Used
- Power BI
- DAX
- Data Modeling
- Business Intelligence
- Excel
- Data Cleaning

## Dataset
The dataset includes transactional sales information used to evaluate business performance across multiple years.

## Author
Jose Antonio Guillen Masis  
Data Analytics | Business Intelligence | Power BI