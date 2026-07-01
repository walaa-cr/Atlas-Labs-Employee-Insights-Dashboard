# Atlas Labs Employee Insights Dashboard

A data-driven HR analytics dashboard for visualizing workforce demographics, performance, and attrition across Atlas Labs. It consolidates multiple views—Overview, Demographics,
Performance Tracker, and Attrition—to support strategic HR decisions and improve organizational health.

---
## Atlas Labs Dashboard

<img width="883" height="497" alt="overview dash" src="https://github.com/user-attachments/assets/28619828-5a7a-4506-87ba-c272a0b4e6dd" />
<img width="880" height="498" alt="Demographics dash" src="https://github.com/user-attachments/assets/c01e619f-810a-40da-b44a-61fb0ead7dce" />
<img width="771" height="497" alt="performance dash f" src="https://github.com/user-attachments/assets/ba99e06d-5c95-4de9-8652-48a504055066" />
<img width="885" height="489" alt="attrition dash f" src="https://github.com/user-attachments/assets/c6937b10-2e1c-45f7-8ea8-bc1a44bf9f48" />







---

## Features

- **Overview Dashboard**
  - Total employees, active vs. attrited
  - Key KPIs (attrition rate, average satisfaction, average tenure)
  - High-level department comparison

- **Demographics Dashboard**
  - Gender distribution
  - Age group breakdown
  - Ethnicity and education level
  - Job role and department composition

- **Performance Tracker**
  - Employee performance ratings
  - Satisfaction scores over time
  - Department-wise performance comparison
  - Identification of high/low performers

- **Attrition Dashboard**
  - Attrition by department, job role, and age group
  - Voluntary vs. involuntary attrition
  - Tenure-based attrition trends
  - Key drivers and risk indicators

---

## Tech Stack

- **Frontend:** Power BI / Tableau / React (depending on implementation)
- **Backend / Data Source:** SQL Server / Excel / CSV / API
- **Data Processing:** Python / Power Query / ETL pipelines


---

## Project Structure

```text
project-root/
├─ data/
│  ├─ atlas_employees_raw.csv
│  ├─ atlas_employees_clean.csv
├─ src/
│  ├─ models/              # Data models, schemas
│  ├─ dashboards/          # Dashboard definitions / PBIX / TWB / components
│  ├─ utils/               # Helper functions, calculations
├─ docs/
│  ├─ screenshots/         # Exported dashboard images
│  └─ Atlas_Insights_Design.md
└─ README.md

