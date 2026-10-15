# Call Centre Trends Dashboard

A Power BI portfolio project for reviewing call-centre operations and service-performance KPIs.

![BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811)
![Focus](https://img.shields.io/badge/Focus-Service%20Analytics-blue)

## Contents
- [Project Overview](#project-overview)
- [Operational Questions](#operational-questions)
- [Dashboard Scope](#dashboard-scope)
- [Metrics to Validate](#metrics-to-validate)
- [Technology Stack](#technology-stack)
- [Repository Structure](#repository-structure)
- [Open the Report](#open-the-report)
- [Limitations and Next Steps](#limitations-and-next-steps)

## Project Overview
The report is intended to make call-centre performance easier to review through a Power BI dashboard. Typical analysis areas include incoming calls, answered calls, service outcomes, and agent performance; exact figures should be read from a refreshed report and validated against its source.

## Operational Questions
- How many calls were received and answered?
- What share of calls were answered or abandoned?
- How do service levels and handling times vary?
- How does performance differ across agents or time periods?

## Dashboard Scope
The repository contains the Power BI report. A separate source CSV, SQL file, notebook, exported KPI table, and screenshot files were not present in the reviewed file inventory.

## Metrics to Validate

| Metric | Recommended definition |
|---|---|
| Total calls | Count of unique call records |
| Answer rate | Answered calls ÷ total calls |
| Abandonment rate | Abandoned calls ÷ total calls |
| Average handling time | Mean handling duration for eligible calls |
| Service level | Calls meeting the defined wait-time threshold ÷ eligible calls |

The report's actual measure definitions may differ. The underlying row count and numeric KPI results could not be independently recalculated from the repository contents, so no call-volume or service-performance figures are claimed here.

## Technology Stack
- **Power BI Desktop:** dashboard and visual reporting.
- **DAX / Power Query:** review the stored calculations and transformations.

## Repository Structure
```text
Call-Centre-Trends/
└── CALL CENTRE TRENDS.pbix
```

## Open the Report
1. Open `CALL CENTRE TRENDS.pbix` in Power BI Desktop.
2. Reconnect the source if prompted.
3. Refresh the model and inspect the filters and measure definitions.
4. Confirm the reporting period and the rules used for answered, abandoned, and eligible calls.

## Limitations and Next Steps
- Add the source dataset and document its schema and provenance.
- Define each KPI and its DAX measure.
- Add genuine screenshots from the report pages.
- Export a summary table to make results independently reproducible.
- Confirm how missing call durations and duplicate records are handled.

## Skills Demonstrated
Business intelligence, operational KPI design, dashboard interpretation, service-performance analysis, and validation of report calculations.
