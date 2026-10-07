# Mobile App Funnel Retention Analytics

##  Project Overview

This project demonstrates an end-to-end Business Analyst and Data Analytics solution for understanding mobile application user behavior, conversion funnel performance, and user retention.

The solution uses a public GA4/Firebase sample dataset available through BigQuery and follows an analytics architecture:

**Firebase / GA4 → BigQuery → SQL Analysis → Looker Studio / Power BI**

The project focuses on identifying funnel drop-offs, measuring cohort retention, defining business KPIs, and creating a structured event tracking plan.

---

##  Business Problem

The mobile application receives users through different acquisition channels, but the business lacks visibility into:

- Where users drop off during the conversion journey
- How many users complete key actions
- Which user cohorts have better retention
- Which acquisition channels generate high-quality users
- What KPIs should be monitored by business stakeholders

The objective is to create a data-driven analytics framework that helps stakeholders understand user behavior and identify opportunities to improve conversion and retention.

---

##  Project Objectives

1. Analyze the mobile application conversion funnel.
2. Identify major user drop-off points.
3. Calculate conversion rates between funnel stages.
4. Build cohort-based retention analysis.
5. Define a KPI tree connecting business goals with operational metrics.
6. Create a GA4/Firebase event taxonomy and tracking plan.
7. Develop SQL-based analytical datasets in BigQuery.
8. Build a business dashboard using Power BI / Looker Studio.
9. Convert analytical findings into actionable business recommendations.

---

##  Solution Architecture

```text
Firebase / GA4
      ↓
GA4 Event Data
      ↓
BigQuery
      ↓
Data Cleaning & Transformation
      ↓
SQL Analytical Models
      ↓
┌─────────────────────┐
│ Funnel Analysis     │
│ Retention Analysis  │
│ User Segmentation   │
│ KPI Calculation     │
└─────────────────────┘
      ↓
Power BI / Looker Studio
      ↓
Business Insights
      ↓
Decision Making
```

---

## Key Analysis Areas

### 1. Funnel Analysis

The user journey is analyzed across important application events.

Example funnel:

```text
App Open
   ↓
Session Started
   ↓
Product / Content Viewed
   ↓
Add to Cart / Key Action
   ↓
Checkout / Conversion Started
   ↓
Purchase / Conversion Completed
```

The analysis identifies:

- Users entering each stage
- Users progressing to the next stage
- Stage-to-stage conversion rate
- Overall funnel conversion
- Drop-off percentage
- Highest drop-off stage

---

### 2. Cohort Retention Analysis

Users are grouped into cohorts based on their first interaction date.

Retention is measured across:

- Day 0
- Day 1
- Day 7
- Day 14
- Day 30

Example:

| Cohort | D0 | D1 | D7 | D14 | D30 |
|---|---:|---:|---:|---:|---:|
| Week 1 | 100% | 42% | 24% | 18% | 12% |
| Week 2 | 100% | 45% | 26% | 20% | 14% |
| Week 3 | 100% | 40% | 22% | 16% | 11% |

The objective is to identify whether newer user cohorts are improving or declining in retention.

---

##  KPI Tree

### Business Goal

**Increase Mobile App Revenue**

```text
Revenue
│
├── Number of Purchasing Users
│   ├── Active Users
│   ├── Engaged Users
│   └── Conversion Rate
│
└── Revenue per Purchasing User
    ├── Average Order Value
    ├── Purchase Frequency
    └── Repeat Purchase Rate
```

### Supporting KPIs

- DAU
- WAU
- MAU
- New Users
- Returning Users
- Engagement Rate
- Funnel Conversion Rate
- Drop-off Rate
- Purchase Conversion Rate
- D1 Retention
- D7 Retention
- D30 Retention
- Average Revenue per User
- Average Order Value

---

##  Business Analyst Deliverables

This project includes:

- Business Requirements Document
- Scope Document
- Stakeholder Map
- Success Metrics
- Event Taxonomy
- Tracking Plan
- Data Dictionary
- User Stories
- Acceptance Criteria
- Use Cases
- UAT Test Cases
- Dashboard Requirements
- KPI Tree
- Business Insights

---

##  BA Role in the Project

As the Business Analyst, I was responsible for:

- Understanding the business objective and analytical requirements.
- Translating business questions into measurable KPIs.
- Defining the mobile app user journey and funnel stages.
- Creating the event taxonomy and tracking requirements.
- Documenting functional and analytical requirements.
- Defining user stories and acceptance criteria.
- Working with data requirements for BigQuery.
- Validating SQL outputs against business definitions.
- Defining dashboard requirements and KPI specifications.
- Analyzing funnel and retention results.
- Converting data findings into actionable business recommendations.

---

##  Tools & Technologies

| Area | Technology |
|---|---|
| Data Source | GA4 / Firebase Sample Dataset |
| Data Warehouse | Google BigQuery |
| Querying | SQL |
| Dashboard | Power BI / Looker Studio |
| Documentation | BRD / User Stories / UAT |
| Data Analysis | SQL / Power BI |
| Visualization | Power BI / Looker Studio |

---

##  Expected Business Outcomes

The solution is designed to help stakeholders:

- Identify the biggest funnel bottleneck.
- Understand user retention behavior.
- Compare retention across cohorts.
- Monitor acquisition and conversion performance.
- Identify high-value user segments.
- Improve product onboarding and conversion.
- Establish a standardized analytics KPI framework.
- Improve event tracking consistency.

---

##  Data Privacy

This portfolio project uses publicly available/sample analytics data.

No confidential company data, customer information, production credentials, or proprietary business information is included.

---

##  Project Structure

```text
01_Business_Requirements
02_Tracking_Plan
03_Data
04_SQL
05_Analysis
06_Dashboard
07_BA_Documentation
08_Project_Deliverables
```

---

## Project Status

**Status:** In Progress

The project is being developed as an end-to-end Business Analyst + Data Analyst portfolio project.

---

##  Skills Demonstrated

**Business Analysis:**  
Requirements Elicitation · BRD · User Stories · Acceptance Criteria · UAT · KPI Definition · Stakeholder Analysis

**Data Analytics:**  
SQL · BigQuery · Funnel Analysis · Cohort Analysis · Retention Analysis · Data Validation

**BI & Visualization:**  
Power BI · Looker Studio · KPI Dashboards · Data Storytelling

**Product Analytics:**  
GA4 · Firebase · Event Taxonomy · Tracking Plan · User Journey Analysis
