# Formula1 Racing Project using Azure Databricks, ADLS & ADF

This repository serves as documentation for a Formula1 Racing project created using Azure services for data engineering. The project aims to process Formula 1 racing data, create an automated data pipeline, and make the data available for presentation and analysis purposes.


## Formula 1 Racing Project Overview

### Required Information
The Formula 1 racing project involves processing data for both driver champions and constructor champions. Points are awarded based on the finishing position in each race, and there are separate championships for drivers and constructors. Pole positions are determined through qualifying races.

### Data Source
The data is sourced from the Ergest Developer API, providing tables such as circuits, races, constructors, drivers, results, pitstops, lap times, and qualifying.

[ER Diagram](http://ergast.com/images/ergast_db.png)

## Project Resources and Architecture

### Azure Services Used
1. **Azure Databricks**: For compute using Python & SQL.
2. **Azure Data Lake Gen2 (Delta Lake / LakeHouse)**: For hierarchical storage and utilizing delta tables.
3. **Azure Data Factory**: For pipeline orchestration for Databricks Notebook.
4. **Azure Key Vault**: For storing secrets for ADLS credentials used in the Databricks Notebook.

Project Architecture:
![image](https://github.com/user-attachments/assets/3d1676c7-3c47-4e7a-b2f1-d315bff24a19)

