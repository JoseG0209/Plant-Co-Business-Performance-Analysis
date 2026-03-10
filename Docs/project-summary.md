# Project Summary

## Overview
This Power BI project analyzes Plant Co. business performance from 2022 to 2024 using an interactive dashboard.

The report allows users to dynamically switch between three key business metrics:
- Gross Profit
- Quantity
- Sales

It also includes year-based filtering and comparative analysis using YTD, PYTD, YTD vs PYTD, and GP%.

## Objective
The objective of this project is to evaluate business performance across time, countries, and products through an interactive and well-structured Power BI dashboard.

## Data Model
The model follows a dimensional structure composed of:
- Fact_Sales
- Dim_Date
- Dim_Product
- Dim_Account
- Slc_Values
- _Measures

This structure supports efficient filtering, metric switching, and time-based analysis.

## Main Features
- Dynamic metric selector
- Year filter
- YTD and PYTD comparison
- Gross Profit Percentage (GP%)
- Country-level analysis
- Product-level analysis
- Monthly trend analysis

## Measures and Logic
The report uses DAX measures organized in a dedicated measures table, including:
- YTD
- PYTD
- GP%
- SWITCH logic for metric selection

This allows the dashboard to update visuals dynamically depending on the selected business metric.

## Analysis Scope
The dashboard is designed to help users analyze performance from multiple perspectives, including:
- time
- country
- product
- profitability
- sales volume

It supports business evaluation by comparing current and previous year results from 2022 to 2024.

## Key Insights
- The dashboard provides flexible analysis across Gross Profit, Quantity, and Sales.
- The data model supports clean and scalable reporting.
- Time intelligence measures improve year-over-year comparison.
- Country and product breakdowns help identify performance patterns.