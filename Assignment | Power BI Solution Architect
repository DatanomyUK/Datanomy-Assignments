Power BI Solution Architect Assignment

# Introduction

This assignment is designed for candidates applying for the role of Power BI Solution Architect. The task involves two main sections: creating a Power BI report and developing a solution design document for the Power BI report. This document provides the necessary requirements and instructions to complete both sections effectively.
Please make necessary assumptions where needed and include an reason behind these assumptions

The report is requested by SwiftCabs Ltd, aiming to understand the current New York taxi market. The company intends to use the insights from this report to evaluate the feasibility of launching a new taxi service in New York.

## Section 1: Power BI Report Creation

### Objective

Analyze New York Yellow Taxi Trip Data for December 2023 and January 2024 using advanced Power BI techniques such as DAX calculations, calculation groups, and field parameters. This report serves as a Proof of Concept (PoC) for two months of data.

## Data Source ##
[Data source](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

## Data Import and Preparation ##

- **Import Data**: Import the Yellow Taxi Trip Records (PARQUET) datasets for **December 2023** and **January 2024** from the NYC Taxi & Limousine Commission (TLC) website into Power BI Desktop.

- **Data Modelling**:
    - Create a Date Dimension table.
    - Establish relationships between the Date Dimension table and the relevant date fields within the Yellow Taxi Trip Records dataset.
    - Import the Taxi Zone Lookup Table (CSV) and Taxi Zone Shapefile (PARQUET).
    - Create relationships between these tables and the location fields in the Yellow Taxi Trip Records dataset.

Measures and DAX Calculations
- **Construct Essential Metrics**:
    - Total Trips
    - Total Fare Amount
    - Average Trip Distance
    - Average Tip Amount
- **Implement Advanced DAX Calculations**:
    - **Peak Hours**: Compute the average trip duration and total trips during various hours of the day.
    - **Popular Routes**: Identify the most frequented pick-up and drop-off locations based on trip counts.
    - **Trip Distance Analysis**: Calculate the distribution of trip distances.
    - **Tip Percentage**: Calculate the average tip percentage based on the fare amount and tip amount.
    - **Profitability by Location**: Analyze the average fare and tip amount for different pick-up and drop-off locations.

- **Calculation Groups for Time Intelligence**
    - Develop a calculation group for time intelligence calculations, including:
    - Year-to-Date (YTD)
    - Month-to-Date (MTD)
    - Previous Year (PY)
    - Same Period Last Year (SPLY)
    - Apply these calculations to appropriate measures to monitor performance over time.

- **Field Parameters**
    - Establish field parameters to dynamically switch between different metrics on visuals.

- **Report Design and Visualizations**
    - Design an interactive report presenting insights from the data analysis.
    - Utilize diverse visuals like maps, charts, and tables to present findings effectively.
    - Include slicers and filters to facilitate data exploration.

\---

## Section 2: Solution Design Document

### Objective

Create a comprehensive solution design document for the Power BI report developed in Section 1. This document should outline the technical solution, data flow, and system components. Additionally, consider how this PoC can be scaled for production use with at least 24 months of data, addressing challenges related to data volume.

Requirements for the Solution Design Document

- **Specify the Problem Clearly**:
    - Ensure the business goals and challenges the solution aims to address are understood. For example, analyzing taxi trip data to understand customer behavior and optimize pricing strategies. **SwiftCabs** seeks to use this information to assess the feasibility of launching a new taxi service in New York.
- **Outline the Data Sources**:
    - Provide details about the "Yellow Taxi Trip Records" dataset (for December 2023 and January 2024) and its format (PARQUET). Include relevant data dictionaries and metadata from the TLC.
- **Define the Target Audience**:
    - Specify who will use this solution, their technical skills, and analytical needs. For instance, whether end-users are data analysts familiar with Power BI or non-technical audiences needing insights.
- **Set Expectations for the Level of Detail**:
    - Indicate if the solution design should include specific DAX calculations or Power BI visualizations or focus on overall architecture and data flow.
- **Specify Constraints**:
    - Note any budget limitations, time constraints, or specific technologies that must be used.
- **Articulate Deliverables Clearly**:
    - Expected contents of the solution design document:
    - Data model design
    - Data transformation and cleaning processes
    - Proposed DAX calculations and measures
    - Mockups of potential Power BI reports and dashboards
    - Architecture diagrams showing data flow and system components
    - Security and access control considerations
- **Considerations for Scaling Up to Production**:
    - Discuss the implications of scaling up from two months of data to at least 24 months. Address challenges such as data storage, processing times, and performance optimization.
    - Highlight strategies for managing increased data volume, such as incremental data refreshes, partitioning large tables, and optimizing DAX queries.
    - Evaluate potential improvements in infrastructure, such as upgrading to a dedicated SQL database or Azure Synapse Analytics, to handle larger datasets efficiently.
- **Establish Review and Approval Processes**:
    - Outline how the solution design will be reviewed and approved, and identify stakeholders involved in the process.

## Submission of the assignment ##

Please submit the Power BI report and the solution design document using a document sharing platform such as OneDrive or Google Drive
