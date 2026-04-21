# NST DVA Capstone 2 - Project Repository

> **Newton School of Technology | Data Visualization & Analytics**
> A 2-week industry simulation capstone using Python, GitHub, and Tableau to convert raw data into actionable business intelligence.

---

## Project Overview

| Field               | Details                                                 |
| ------------------- | ------------------------------------------------------- |
| **Project Title**   | Uber & Ola Ride Analytics and Cancellation Optimization |
| **Sector**          | Transportation / Ride-Hailing Services                  |
| **Team ID**         | Group 4                                                 |
| **Section**         | C                                                       |
| **Faculty Mentor**  | *To be filled*                                          |
| **Institute**       | Newton School of Technology                             |
| **Submission Date** | Apr 17 – Apr 28, 2026                                   |

---

### Team Members

| Role | Name | GitHub Username |
|---|---|---|
| Project Lead | Rudraksh Rathod | `Rudra-codee` |
| Data Lead | _Name_ | `github-handle` |
| ETL Lead | Akhil Nath reddy | `akhilnathreddy` |
| Analysis Lead | Meka Chaitanya Sai | `github-handle` |
| Visualization Lead | Manas Aniruddha Selukar | `manas-2212` |
| Strategy Lead | Akhil Sharma | `github-handle` |
| PPT and Quality Lead | Dev Jindal| `Devjin27` |

## Business Problem

This project focuses on analyzing ride booking and cancellation patterns in ride-hailing services such as Uber and Ola. The goal is to identify inefficiencies in service delivery, understand customer and driver behavior, and improve overall operational performance.

**Core Business Question**

> How can ride booking patterns and cancellation behavior be analyzed to reduce cancellations, improve service reliability, and optimize ride allocation across time, location, and vehicle types?

**Decision Supported**

> This analysis enables stakeholders to identify high-cancellation scenarios and take actions such as optimizing driver allocation during peak hours, improving matching efficiency, adjusting pricing strategies, and enhancing overall customer experience.

---

## Dataset

| Attribute               | Details                                                                                   |
| ----------------------- | ----------------------------------------------------------------------------------------- |
| **Source Name**         | Kaggle                                                                                    |
| **Direct Access Link**  | https://www.kaggle.com/datasets/hetmengar/ola-and-uber-ride-booking-and-cancellation-data |
| **Row Count**           | ~103,000                                                                                  |
| **Column Count**        | 13+                                                                                       |
| **Time Period Covered** | July 2024                                                                                 |
| **Format**              | CSV                                                                                       |

**Key Columns Used**

| Column Name         | Description                                       | Role in Analysis            |
| ------------------- | ------------------------------------------------- | --------------------------- |
| Booking Status      | Indicates whether ride was completed or cancelled | KPI (Cancellation Rate)     |
| Pickup Location     | Starting location of ride                         | Location analysis           |
| Drop Location       | Ending location of ride                           | Demand patterns             |
| Vehicle Type        | Type of ride selected                             | Segmentation                |
| Booking Value       | Total fare of ride                                | Revenue KPI                 |
| Ride Distance       | Distance of ride                                  | Pricing & behavior analysis |
| Payment Method      | Mode of payment used                              | Customer behavior analysis  |
| Cancellation Reason | Reason for cancellation                           | Root cause analysis         |
| Date & Time         | Timestamp of booking                              | Time-based trends           |

---

## KPI Framework

| KPI                        | Definition                     | Formula / Computation                 |
| -------------------------- | ------------------------------ | ------------------------------------- |
| Ride Cancellation Rate (%) | Percentage of rides cancelled  | (Cancelled Rides / Total Rides) × 100 |
| Average Ride Value         | Average revenue per ride       | Total Booking Value / Total Rides     |
| Completion Rate (%)        | Percentage of successful rides | (Completed Rides / Total Rides) × 100 |

---

## Tableau Dashboard

| Item                 | Details                                                                                              |
| -------------------- | ---------------------------------------------------------------------------------------------------- |
| **Dashboard URL**    | *To be added after publishing*                                                                       |
| **Executive View**   | *To be filled*                                                                                       |
| **Operational View** | *To be filled*                                                                                       |
| **Main Filters**     | *To be filled*                                                                                       |

---

## Key Insights

1. Cancellation rates increase during peak hours
2. Certain locations show consistently higher cancellation rates
3. Driver-side cancellations are higher for longer-distance rides
4. Vehicle type significantly impacts completion rates
5. Payment methods influence cancellation behavior
6. High-demand periods lead to service inefficiencies
7. Short-distance rides have higher completion rates
8. Pricing variations impact booking success

---

## Recommendations

| # | Insight                              | Recommendation                                | Expected Impact                 |
| - | ------------------------------------ | --------------------------------------------- | ------------------------------- |
| 1 | High peak-hour cancellations         | Introduce driver incentives during peak hours | Reduced cancellations           |
| 2 | Location-based cancellation hotspots | Improve driver allocation in high-risk areas  | Better service reliability      |
| 3 | Vehicle imbalance                    | Optimize vehicle distribution                 | Improved operational efficiency |
| 4 | Payment-related cancellations        | Improve payment processing systems            | Enhanced user experience        |

---

## Repository Structure

```text
SectionName_TeamID_ProjectName/
|
|-- README.md
|
|-- data/
|   |-- raw/
|   `-- processed/
|
|-- notebooks/
|   |-- 01_extraction.ipynb
|   |-- 02_cleaning.ipynb
|   |-- 03_eda.ipynb
|   |-- 04_statistical_analysis.ipynb
|   `-- 05_final_load_prep.ipynb
|
|-- scripts/
|   `-- etl_pipeline.py
|
|-- tableau/
|   |-- screenshots/
|   `-- dashboard_links.md
|
|-- reports/
|   |-- README.md
|   |-- project_report_template.md
|   `-- presentation_outline.md
|
|-- docs/
|   `-- data_dictionary.md
```

---

## Tech Stack

| Tool                   | Purpose                  |
| ---------------------- | ------------------------ |
| Python (Pandas, NumPy) | Data cleaning & analysis |
| Jupyter Notebook       | Development & analysis   |
| Tableau Public         | Dashboard visualization  |
| GitHub                 | Version control          |

---

## Analytical Pipeline

1. Define business problem
2. Extract dataset
3. Clean and transform data
4. Perform exploratory data analysis
5. Build Tableau dashboard
6. Generate insights and recommendations
7. Final report and presentation

---

## Evaluation Focus

* Problem clarity
* Data cleaning quality
* Depth of analysis
* Dashboard effectiveness
* Actionable insights

---

*Newton School of Technology - Data Visualization & Analytics | Capstone 2*
