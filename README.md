# Indiana Food Access Data Library – Food Security Analytics

This project was developed under **Heartland Community Network** to support data-driven decision-making around food security and access across Indiana counties.

---

## Problem Statement
Food access data across Indiana existed in fragmented, inconsistent formats spread across public directories, nonprofit websites, and local agency pages. This fragmentation made it difficult for stakeholders to assess geographic coverage, service availability, eligibility constraints, and operational gaps in food assistance services.

---

## Objective
To build a unified, analytics-driven dashboard that consolidates food security data and enables stakeholders at Heartland Community Network and partner organizations to identify underserved regions, access barriers, and operational limitations across counties.

---

## Data & Methodology
- Consolidated data from 15+ public and nonprofit sources covering food pantries, meal programs, mobile services, and nutrition programs.
- Standardized organization details, service types, populations served, eligibility rules, operating schedules, and geographic attributes.
- Applied automated cleaning, deduplication, and schedule parsing to convert unstructured text into analyzable fields.
- Modeled county-, ZIP-, and organization-level metrics to assess coverage, accessibility, and service distribution.
- Built four interactive dashboards to support exploratory and decision-oriented analysis.

---

## Dashboards

### 1. Geographic Coverage
Analyzes the distribution of food providers across 11 Indiana counties and ZIP codes, highlighting service density, ZIP-level coverage, and counties with low access. Identifies geographic service gaps and potential food deserts.
<img width="1446" height="637" alt="image" src="https://github.com/user-attachments/assets/a11cad74-09c7-4e64-84c5-7b5140313c9b" />


### 2. Providers & Service Types
Examines service diversity across counties, comparing food pantries, meal programs, mobile pantries, and nutrition services. Highlights limited mobile outreach and uneven service variety across regions.

<img width="1454" height="684" alt="image" src="https://github.com/user-attachments/assets/5db414e5-55d4-4101-91a1-a96e5977129c" />


### 3. Eligibility
Evaluates who can access services by analyzing open-access versus restricted providers and the populations served. Reveals access barriers caused by eligibility requirements and gaps in support for vulnerable groups.

<img width="1500" height="642" alt="image" src="https://github.com/user-attachments/assets/f359cab1-9831-455b-af35-b944fdc9d262" />


### 4. Temporal Operations
Assesses service availability by day of week and operating hours. Identifies limited evening and weekend coverage that restricts access for working individuals and families.

<img width="1481" height="606" alt="image" src="https://github.com/user-attachments/assets/26f7a75a-26da-44ad-975c-3f3ce1d2f01c" />


---

## Key Results
- Only 31% of ZIP codes across the region have at least one food provider.
- 5 of 11 counties show low ZIP-level coverage (<25%).
- Food pantries dominate service offerings, while mobile and weekend services are limited.
- 86% of providers have eligibility restrictions, limiting universal access.
- Rural counties face compounded challenges of low service density and limited operating hours.

---

## Tools
- Python (data collection, cleaning, schedule parsing)
- SQL (data validation, querying, and aggregation in BigQuery)
- BigQuery (data validation and storage)
- Tableau (interactive dashboards)

---

## Organization
This project was completed as part of a data analytics initiative with **Heartland Community Network**, supporting regional food security planning and outreach.
