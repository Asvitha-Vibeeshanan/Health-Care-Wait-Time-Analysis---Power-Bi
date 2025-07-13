# Health Care Wait Time Analysis - Power-Bi

## Project Objective

This Power BI dashboard is designed to:
- Track the current status of the **Patient waiting list**.
- Compare **Inpatient**, **Outpatient**, and **Day Case** categories.
- Analyze **historical trends** in patient wait times between 2018 and 2021.
- Enable **granular analysis** at the specialty and age profile level.

## Dataset Overview

| File Name            | Description                                                  |
|----------------------|--------------------------------------------------------------|
| `Op_WL 2018.csv`     | Outpatient data for 2018                                     |
| `Op_WL 2019.csv`     | Outpatient data for 2019                                     |
| `Op_WL 2021.csv`     | Outpatient data for 2021                                     |
| `IN_WL 2018.csv`     | Inpatient data for 2018                                      |
| `IN_WL 2019.csv`     | Inpatient data for 2019                                      |
| `IN_WL 2020.csv`     | Inpatient data for 2020                                      |
| `IN_WL 2021.csv`     | Inpatient data for 2021                                      |
| `Mapping_Specialty.csv` | Maps specialty codes to readable specialty names        |

Each record includes:
- Archive Date
- Specialty & Age Category
- Time Band (e.g., 0–3 months, 6–9 months, etc.)
- Total Wait List Count


## Dashboard Views

### Summary Page
- Total Wait List Comparison (Latest vs Previous Month)
- Case Type Split – Outpatient, Day Case, Inpatient
- Time Band vs Age Profile – Distribution of wait times across age groups
- Top 5 Specialties by Median Wait Time
- Monthly Trend – Time series of patient volumes (2018–2021)

### Detailed Page
- Filter options for:
  - Date range
  - Specialty
  - Age Profile
  - Time Band
- Interactive table view for drill-down exploration


## Insights & Trends

- **Rising Outpatient Demand**: Grew from 502K (Jul 2018) to 629K (Mar 2021)
- **Stable Inpatient/Day Case Volumes**: Fluctuate around 20K–25K
- **Backlogs**: Longest delays in Paediatric Orthopaedic and Urology specialties
- **Age Band Impact**: Patients aged 16–64 have the highest wait distribution across all time bands
- **Critical Zones**: Many patients waiting over 12 months—especially for surgeries


## Tools & Technologies

- **Power BI Desktop** – Dashboard development and visuals
- **Power Query** – Data transformation
- **CSV** – Data source format
- **DAX** – Custom calculations and metrics

## Explore the Live Dashboard

[Click here to view the Dashboard](https://app.powerbi.com/groups/me/reports/ffbb859a-28ce-455d-8dfb-53717d2fa234/b7c3cacbea47df4217a1?experience=power-bi)

> _Note: Access may require Power BI login permissions._

