# Bank Loan Dashboard Project

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Problem Statement](#problem-statement)
  - [Dashboard 1: Summary](#dashboard-1-summary)
  - [Dashboard 1: Good Loan vs. Bad Loan KPIs](#dashboard-1-good-loan-vs-bad-loan-kpis)
    - [Good Loan](#good-loan)
    - [Bad Loan](#bad-loan)
    - [Loan Status Grid View](#loan-status-grid-view)
  - [Dashboard 2: Overview](#dashboard-2-overview)
  - [Dashboard 3: Details](#dashboard-3-details)
- [Functionalities Covered](#functionalities-covered)
  - [Database and SQL](#database-and-sql)
  - [SQL Server](#sql-server)
  - [Power BI](#power-bi)
- [Contribution](#contribution)

## Overview
This project aims to create an interactive and comprehensive Power BI dashboard for a bank's loan portfolio. The dashboard provides insights into various aspects of loan applications, funding, and repayments, aiding data-driven decision-making.

## Sample Images
[Sample Screenshoots](https://github.com/NobelMitiku/Power-Bi-Sample-Project/tree/master/screen%20shoots)

## Microsoft SQL Server database data
[Data](https://github.com/NobelMitiku/Power-Bi-Sample-Project/tree/master/data)

## Getting Started

To explore and interact with the Bank Loan Dashboard, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/NobelMitiku/Power-Bi-Sample-Project 
1. **Open Power BI::**

- Open Power BI Desktop.
- Load the provided .pbix file from the cloned repository.
2. **Data Source Configuration:**

- Ensure your data sources are correctly linked.
- Update connection strings if necessary.
3. **Exploring the Dashboards:**

- Navigate through the different dashboards (Summary, Overview, Details) using the tabs.
- Interact with the visuals to gain insights.

## Problem Statement

### Dashboard 1: Summary
The first dashboard focuses on high-level Key Performance Indicators (KPIs) related to the bank's loan operations:

- **Total Loan Applications:** Total number of loan applications received within a specific period. Includes Month-to-Date (MTD) Loan Applications and Month-over-Month (MoM) changes.
- **Total Funded Amount:** Total funds disbursed as loans. Includes MTD Total Funded Amount and MoM changes.
- **Total Amount Received:** Total repayments received from borrowers. Includes MTD Total Amount Received and MoM changes.
- **Average Interest Rate:** Average interest rate across all loans. Includes MTD interest rates and MoM variations.
- **Average Debt-to-Income Ratio (DTI):** Average DTI of borrowers. Includes MTD DTI and MoM fluctuations.

### Dashboard 1: Good Loan vs. Bad Loan KPIs
This section differentiates between 'Good' and 'Bad' loans based on certain criteria, providing a breakdown of their respective metrics:

#### Good Loan:
- Good Loan Application Percentage
- Good Loan Applications
- Good Loan Funded Amount
- Good Loan Total Received Amount

#### Bad Loan:
- Bad Loan Application Percentage
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Total Received Amount

#### Loan Status Grid View
A grid view report categorized by 'Loan Status' displaying:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- MTD Funded Amount
- MTD Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)

### Dashboard 2: Overview
This dashboard offers visual insights into lending activities through various charts:

- **Monthly Trends by Issue Date (Line Chart):** Identifies seasonality and long-term trends in lending.
- **Regional Analysis by State (Filled Map):** Highlights regions with significant lending activity and regional disparities.
- **Loan Term Analysis (Donut Chart):** Shows the distribution of loans across different term lengths.
- **Employee Length Analysis (Bar Chart):** Examines how lending metrics vary with borrowers' employment lengths.
- **Loan Purpose Breakdown (Bar Chart):** Provides a breakdown of loan metrics based on loan purposes.
- **Home Ownership Analysis (Tree Map):** Shows how home ownership status affects loan applications and disbursements.

### Dashboard 3: Details
The Details Dashboard consolidates key loan-related metrics and data points into a comprehensive, user-friendly interface for in-depth analysis.

## Functionalities Covered

### Database and SQL
- Creating Databases and Tables
- Selecting Data
- Using `DATENAME`, `DATEPART`, `CAST`, and `DECIMAL` functions
- Grouping and Ordering Data
- Using `LIMIT`, `COUNT`, `DISTINCT`, `CTE`, and `PARTITION`

### SQL Server
- Connecting to SQL Server
- Data Cleaning and Modelling
- Data Processing
- Power Query
- Date Tables and Time Intelligence Functions
- DAX Functions (Date, Text, Filter, Calculate, SUM/SUMX)
- Creating KPIs
- Creating and Formatting Visuals

### Power BI
- Creating Interactive Charts
- Formatting Visuals
- Navigations

## Contribution
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.