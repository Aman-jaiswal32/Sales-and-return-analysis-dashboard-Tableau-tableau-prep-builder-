# Sales-and-return-analysis-dashboard-Tableau-tableau-prep-builder-

# Tableau Prep Sales & Returns Analysis Project

## Overview

This project demonstrates an end-to-end data preparation and dashboard development workflow using Tableau Prep Builder and Tableau.

The objective was to transform fragmented sales and returns data into a clean, analysis-ready dataset and build an interactive dashboard for business insights.

---

## Project Workflow

Raw Data → Data Cleaning → Data Transformation → Union → Join → Feature Engineering → Dashboard

---

## Dataset Structure

### Sales Data

* South_Sales_2015
* South_Sales_2016
* South_Sales_2017
* South_Sales_2018
* North Sales
* Central Sales

### Returns Data

* Returns Dataset

---

## Data Cleaning

### Standardization

* Trimmed unnecessary spaces
* Corrected data types
* Removed redundant columns

### State Name Conversion

Converted abbreviated state names into complete names.

Examples:

* WA → Washington
* CA → California
* NY → New York

### Date Transformation

North region data contained:

* Ship Year
* Ship Month
* Ship Day

These columns were combined into a single Ship Date field.

---

## Data Integration

### Union Operations

Merged all yearly and regional sales datasets into a single master sales dataset.

### Returns Data Preparation

* Cleaned return records
* Split return reason and approver details
* Standardized column formats

### Join Operations

Joined Sales and Returns datasets using:

* Order ID
* Product ID

Removed duplicate key fields generated during the join.

---

## Feature Engineering

### Delivery Days

Calculated the number of days required to deliver an order.

### Return Status

Created a flag indicating whether an order was returned.

---

## Dashboard Features

### KPI Cards

* Total Sales
* Total Orders
* Average Delivery Days
* Returned Orders

### Visualizations

* Sales Trend Analysis
* Sales by Region
* Sales by State
* Return Analysis
* Top Products Analysis
* Delivery Performance Analysis

### Interactive Filters

* Region
* State
* Year
* Return Status

---

## Tools Used

* Tableau Prep Builder
* Tableau Public/Desktop

---

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Wrangling
* ETL Workflow Design
* Data Integration
* Union Operations
* Join Operations
* Feature Engineering
* Dashboard Development
* Data Visualization

---

## Key Learning

A significant portion of analytics work happens before visualization. This project reinforced the importance of preparing clean, reliable, and consistent data before building dashboards and generating insights.
