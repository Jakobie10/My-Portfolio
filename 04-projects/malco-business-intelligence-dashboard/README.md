# Business Intelligence Dashboard for Fleet Performance & Fuel Analytics at MALCO HAULAGE

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-742774?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-00599C?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-0F766E?style=for-the-badge)

> **Designed and developed an end-to-end Business Intelligence solution that transforms operational fleet data into interactive dashboards, enabling data-driven decision-making for fleet performance, fuel consumption, and operational efficiency at MALCO HAULAGE.**

---

| **Project Information** | **Details** |
|-------------------------|-------------|
| **Project Type** | End-to-End Business Intelligence Solution |
| **Role** | Business Intelligence Analyst |
| **Industry** | Logistics & Transportation |
| **Data Source** | Operational Fleet Dispatch Records (February–June 2026) |
| **Database** | PostgreSQL |
| **Visualization Tool** | Microsoft Power BI |
| **Supporting Tools** | Microsoft Excel, Power Query |
| **Project Status** | Completed |
| **Focus Areas** | Fleet Performance, Fuel Analytics, Route Analysis, Operational Efficiency |
| **Skills Applied** | SQL, PostgreSQL, DAX, Data Modeling, Dashboard Design, KPI Development, Business Analytics |

---

## 📋 Executive Summary

This project presents an end-to-end Business Intelligence solution developed to improve operational visibility and support data-driven decision-making for MALCO HAULAGE, a logistics and transportation company.

Operational dispatch data covering February through June 2026 was imported into PostgreSQL, where SQL queries were used to analyze fleet performance, fuel consumption, trip activity, and route efficiency. The processed data was then connected to Microsoft Power BI, where Power Query, data modeling, and DAX measures were used to create interactive dashboards and executive reports.

The solution delivers four dashboards that answer key business questions related to fleet operations:

- Executive Overview
- Trip Performance
- Fuel Consumption
- Fleet Efficiency Analysis

Together, these dashboards enable management to monitor operational KPIs, evaluate fuel usage, identify high-performing trucks and routes, and support faster, evidence-based decision-making.

This project demonstrates my ability to manage the complete Business Intelligence workflow—from data preparation and SQL analysis to dashboard development and business storytelling.

---

## 🎯 Business Challenge

MALCO HAULAGE generates operational dispatch records every day, capturing information such as dispatch dates, truck assignments, destinations, fuel (AGO) issued, and distance travelled. Although this data is valuable for monitoring fleet performance, it was stored as operational records that provided limited visibility into business performance and operational trends.

Management needed a reporting solution capable of transforming raw dispatch data into meaningful insights that could answer important business questions, including:

- How many trips were completed during the reporting period?
- How far did the fleet travel?
- How much AGO was issued for operations?
- Which trucks consumed the most fuel?
- Which routes required the longest travel distances?
- Which trucks and routes operated most efficiently?

Without an interactive reporting system, answering these questions required manual calculations and spreadsheet analysis, making decision-making slower and limiting management's ability to identify operational trends.

The objective of this project was to design a Business Intelligence solution that transforms operational dispatch records into interactive dashboards that support faster, more informed, and data-driven decision-making.

---

## 🏗️ Solution Architecture

```text
                Fleet Dispatch Records (CSV)
                           │
                           ▼
                    PostgreSQL Database
                           │
                           ▼
                   SQL Data Analysis
                           │
                           ▼
            Power Query (Data Preparation)
                           │
                           ▼
          Data Modeling & DAX Measures
                           │
                           ▼
              Microsoft Power BI Reports
                           │
                           ▼
     Interactive Dashboards & Business Insights
```

### Architecture Overview

Monthly fleet dispatch records covering February through June 2026 were imported into a PostgreSQL database, where SQL queries were used to explore operational performance and answer key business questions. The dataset was then connected to Microsoft Power BI, where Power Query was used for data preparation and transformation.

A dedicated calendar table and DAX measures were created to support time-based analysis, KPI calculations, and interactive filtering. The completed data model powers four interactive dashboards that provide management with actionable insights into fleet performance, fuel consumption, trip activity, and operational efficiency.

---

## 📊 Dashboard Overview

The Business Intelligence solution consists of four interactive dashboards, each designed to answer specific business questions and support operational decision-making.

### 1. Executive Overview Dashboard

Provides a high-level summary of fleet operations through key performance indicators (KPIs), including total trips, total distance travelled, AGO issued, fuel efficiency, and monthly operational trends.

### 2. Trip Performance Dashboard

Analyzes fleet activity by highlighting average trip distance, longest and shortest routes, most frequently used trucks, and the longest operational routes during the reporting period.

### 3. Fuel Consumption Dashboard

Monitors AGO usage through fuel consumption trends, average fuel issued per trip, gas cuts, and identifies the trucks with the highest fuel consumption.

### 4. Fleet Efficiency Analysis Dashboard

Evaluates operational efficiency by comparing fuel efficiency across trucks and routes, enabling management to identify high-performing assets and opportunities for operational improvement.

---

