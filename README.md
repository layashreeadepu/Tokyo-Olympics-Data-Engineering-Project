# Tokyo Olympics Data 🏅

This repository contains data related to the Tokyo Olympics, specifically focusing on Athletics events, including information about athletes, coaches, entries by gender, medals won, and participating teams.

## Data Azure End-to-End Project 🚀

This dataset has been curated as part of an end-to-end data engineering project completed on Azure. The project involved utilizing Azure's Data Analytics, Data Lake, Data Warehouse, Databricks, and Power BI services to create a comprehensive data pipeline.

## Athletics Data 🏃‍♂️

### Athletes
- **PersonName**: Name of the athlete
- **Country**: Representing country of the athlete
- **Discipline**: Athletic discipline of the athlete

### Coaches
- **Name**: Name of the coach
- **Country**: Country the coach represents
- **Discipline**: Athletic discipline the coach specializes in
- **Event**: Event the coach is associated with

### Entries by Gender
- **Discipline**: Athletic discipline
- **Female**: Number of female athletes entered
- **Male**: Number of male athletes entered
- **Total**: Total number of athletes entered

### Medals 🥇🥈🥉
- **Rank**: Overall rank of the team based on total medals won
- **Team_Country**: Country of the team
- **Gold**: Number of gold medals won
- **Silver**: Number of silver medals won
- **Bronze**: Number of bronze medals won
- **Total**: Total number of medals won
- **Rank by Total**: Rank based on total medals won

### Teams
- **TeamName**: Name of the team
- **Discipline**: Athletic discipline the team is associated with
- **Country**: Country the team represents
- **Event**: Event the team participates in

## Project Components

- **Data Ingestion**: Data is ingested into Azure Data Lake Storage using Azure Data Factory pipelines.
   
- **Data Processing**: Raw data is processed using Azure Databricks for tasks such as data cleansing, transformation, and feature engineering.

- **Data Storage**: Processed data is stored in Azure Data Lake Storage for further analysis and in Azure Data Warehouse for optimized querying.

- **Data Analysis**: Azure Databricks is used for exploratory data analysis and deriving insights from the data.

- **Data Visualization**: Power BI is utilized to create interactive dashboards and reports to visualize key insights and trends.
