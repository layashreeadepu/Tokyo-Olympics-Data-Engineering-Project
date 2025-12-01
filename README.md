# Tokyo Olympics Data Engineering Project 🏅

This project showcases an end-to-end data engineering pipeline built on **Microsoft Azure**, using data from the **Tokyo Olympics (Athletics events)**. It integrates ingestion, transformation, storage, analysis, and visualization of Olympic datasets, offering rich insights into athlete participation, performance, and medal distribution.

## 🏃‍♀️ Project Motivation

Olympic datasets offer valuable insights into **global sports trends, gender participation, and national performance metrics**. This project was designed to replicate a real-world data engineering scenario by building a scalable pipeline using Azure's cloud ecosystem.

---

## 📊 Dataset Overview

The dataset focuses on **Athletics events** during the Tokyo Olympics and includes the following tables:

- **Athletes**
  - `PersonName`: Athlete’s name  
  - `Country`: Representing country  
  - `Discipline`: Athletic discipline  

- **Coaches**
  - `Name`: Coach’s name  
  - `Country`: Representing country  
  - `Discipline`: Specialization  
  - `Event`: Event associated  

- **Entries by Gender**
  - `Discipline`, `Female`, `Male`, `Total`  

- **Medals**
  - `Team_Country`, `Gold`, `Silver`, `Bronze`, `Total`, `Rank`, `Rank by Total`  

- **Teams**
  - `TeamName`, `Discipline`, `Country`, `Event`

---

## 🎯 Business Objectives

- Enable data-driven insights into **medal trends, team performance**, and **gender representation**
- Facilitate **real-time analytics and reporting** using cloud-native tools
- Showcase cloud-based orchestration and analytics with **Azure**

---

## ☁️ Architecture & Tools

| Layer              | Tools & Services Used                                                                 |
|-------------------|----------------------------------------------------------------------------------------|
| Data Ingestion     | **Azure Data Factory**                                                                |
| Data Storage       | **Azure Data Lake Storage**, **Azure Synapse Analytics**                              |
| Data Processing    | **Azure Databricks (PySpark)**                                                        |
| Data Analysis      | **Exploratory Data Analysis (EDA)** in **Databricks Notebooks**                       |
| Data Visualization | **Power BI Dashboards**                                                               |

---

## 🔄 Data Pipeline Steps

1. **Data Ingestion**  
   Raw CSV files ingested into Azure Data Lake via **ADF pipelines**

2. **Data Cleansing & Transformation**  
   Performed in **Azure Databricks** using PySpark (handling nulls, deduplication, and formatting)

3. **Data Storage**  
   - Raw & curated layers in **Data Lake**  
   - Analytical layer in **Azure Synapse Analytics** for BI querying  

4. **Exploratory Analysis**  
   Conducted on transformed datasets using PySpark and SQL in **Databricks**

5. **Reporting**  
   **Power BI** reports and dashboards built from Synapse to track medal rankings, team participation, and gender distribution

---

## 📌 Key Insights

- Top-performing countries in Athletics based on total medals
- Gender participation trends across disciplines
- Events with highest representation by country

---

## 📈 Visualizations

Interactive reports created in Power BI to display:
- Medal tallies by country
- Gender-based participation
- Discipline-specific analysis

> *Visual samples available in `/images/` or linked dashboards.*

---

## 🧠 Skills & Tools Used

- **Cloud**: Azure Data Factory, Azure Data Lake, Azure Databricks, Azure Synapse
- **Data Processing**: PySpark, SQL
- **Visualization**: Power BI
- **Data Engineering Concepts**: ETL pipeline, EDA, Cloud Storage, Distributed Processing

---
