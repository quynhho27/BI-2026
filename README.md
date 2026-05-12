# FMCG Supply Chain & Operations BI Project

# Project Overview

This project focuses on building an end-to-end Business Intelligence (BI) solution for an FMCG company facing operational inefficiencies due to the lack of an effective management and monitoring system.

The company experienced revenue loss and delivery performance issues but lacked visibility into the root causes. This project was developed to analyze operational performance, identify business problems, and provide data-driven KPI recommendations and strategic solutions.

The project covers the complete BI workflow:

> Database → ETL Pipeline → Data Warehouse → Operational Dashboard → Data Analysis → Business Problems → Solutions & KPI Recommendations



# Business Objective

The FMCG company encountered several operational challenges:
- Revenue leakage caused by low fulfillment performance
- High percentage of delayed deliveries
- Lack of centralized operational monitoring
- Difficulty identifying the root causes of business issues

### Project Objectives
- Analyze the causes of revenue leakage
- Identify factors contributing to delivery delays
- Build a centralized operational monitoring system
- Develop dashboards for business visibility
- Generate KPI recommendations and strategic insights

This project builds a complete end-to-end BI process from:
- Database management
- Data warehousing
- Dashboard development
- Operational analysis
- Business problem identification
- Strategic KPI recommendations

# Project Workflow

```text
Source Data
    ↓
Supabase Database
    ↓
Airflow ETL Pipeline
    ↓
BigQuery Data Warehouse
    ↓
Power BI Operational Dashboard
    ↓
Python Analysis (Jupyter Notebook)
    ↓
Business Insights & KPI Recommendations
```

# Key Steps

## 1. Data Collection & Database Management
Operational datasets were collected, cleaned, and loaded into a relational database using **Supabase**.

### Tasks:
- Data aggregation
- Data cleaning
- Database storage
- Data organization


## 2. ETL Process & Scheduling
An automated ETL pipeline was developed using **Apache Airflow**.

### Tasks:
- Extract operational data
- Transform and clean datasets
- Automate scheduling workflows
- Load processed data into the warehouse


## 3. Data Warehouse Development
Processed data was loaded into **Google BigQuery** to support scalable analytics and dashboard performance.


## 4. Operational Dashboard Development
Interactive dashboards connected to Google Big Query were developed in **Power BI** to monitor operational performance.

### Main Metrics:
- OT % (On-Time Delivery)
- IF % (In-Full Delivery)
- OTIF %
- Line Fill Rate (LIFR)
- Volume Fill Rate (VOFR)


## 5. Data Analysis & Problem Identification
Using **Python** and **Jupyter Notebook**, operational data was analyzed to identify business problems and their root causes.


# Business Problems Identified

## Problem 1: Revenue Leakage Due to Low Fill Rate

### Findings
- Revenue leakage reached approximately **3.4%**
- Main contributor: low **Line Fill Rate (LIFR)**

### KPI Recommendation
Increase **Volume Fill Rate by 3.4%** to reduce approximately **3.1% revenue leakage** based on regression analysis.


## Problem 2: High Delayed Delivery Rate

### Findings
- More than **30%** of deliveries were delayed
- Delivery delays negatively affected operational performance

### KPI Recommendation
- Reduce delayed delivery rate to **below 18%**
- Reduce average delay days to **under 1 day**



# Business Value

This project demonstrates how Business Intelligence systems can:
- Improve operational visibility
- Support data-driven decision making
- Detect performance bottlenecks
- Reduce revenue leakage
- Optimize supply chain operations
- Establish measurable KPIs for continuous improvement

# ⚙️ Tools & Technologies

| Category | Tools |
|---|---|
| Database | Supabase |
| ETL & Scheduling | Apache Airflow |
| Data Warehouse | Google BigQuery |
| BI Dashboard | Power BI |
| Data Analysis | Python |
| Notebook Environment | Jupyter Notebook |
| Python Libraries | Pandas, Matplotlib, Seaborn |


# Key Outcomes

- Built a complete end-to-end BI architecture
- Automated ETL pipeline using Airflow
- Developed operational dashboards for monitoring KPIs
- Identified operational inefficiencies through data analysis
- Quantified revenue leakage caused by fulfillment issues
- Proposed KPI targets and strategic recommendations
- Demonstrated practical BI and analytics workflow for FMCG operations

