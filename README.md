# Customer Support Resolution Time Analysis | Power BI

## Project Overview

This project uses Microsoft Power BI to analyze 20,000 customer support tickets and investigate factors associated with long ticket resolution times.

The dashboard examines resolution trends, escalations, reopened tickets, queue backlog, ticket priority, issue types, and agent-level performance.

## Business Problem

Long customer support resolution times can affect customer satisfaction, increase operational workload, and reduce support team efficiency.

The objective of this project is to identify patterns associated with longer resolution times and provide actionable recommendations for customer support managers.

## Project Objectives

- Measure overall ticket volume and resolution time.
- Compare average and median resolution times.
- Examine the relationship between escalations and resolution time.
- Investigate reopened tickets and their potential operational impact.
- Compare resolution times across ticket priorities and issue types.
- Examine agent-level performance and queue backlog.

## Tools and Technologies

- Microsoft Power BI — dashboard development and visualization.
- DAX — KPI calculations and analytical measures.
- CSV / Microsoft Excel — data storage and preparation.

## Key Performance Indicators

- Total Tickets
- Reopened Tickets
- Average Resolution Time
- Median Resolution Time
- Average Queue Backlog
- Escalated Tickets
- Escalation Rate

## Dashboard Visualizations

- Monthly resolution time trend.
- Customer segment analysis.
- Average resolution time by escalation status.
- Agent-level performance comparison.
- Average resolution time by ticket priority.
- Reopened ticket analysis.
- Resolution time by issue type.

## Initial Dashboard Observations

Based on the dashboard screenshot:

- The dataset contains 20,000 tickets.
- The reported average resolution time is 53.04, while the median is 49.10.
- The dashboard reports 7,581 reopened tickets.
- It reports 4,475 escalated tickets and an escalation rate of 22.38%.
- The displayed average resolution time is higher for escalated tickets than for non-escalated tickets.
- The priority comparison shows higher displayed resolution times for Critical and High priority tickets than for Low and Medium priority tickets.

These are initial observations from the dashboard. The units of resolution time, the KPI definitions, and the underlying calculations should be validated before drawing final conclusions.

## Business Recommendations

- Investigate why escalated tickets take longer to resolve and identify opportunities to improve escalation workflows.
- Review reopened tickets to identify recurring problems, incomplete resolutions, or opportunities to improve first-contact resolution.
- Prioritize investigation of Critical and High priority tickets to identify avoidable delays.
- Monitor queue backlog and allocate support resources where workload and delays are greatest.
- Compare agent performance alongside ticket complexity, workload, and case mix to ensure fair evaluation.
- Track average and median resolution time together to understand typical performance and the impact of unusually long-running tickets.

## Dashboard Preview

![Customer Support Resolution Time Analysis Dashboard](dashboard.png)

## Project Files

- `Customer_Support_Dashboard.pbix` — Power BI report file.
- `Customer_Support_Dataset.xlsx` — source dataset.
- `dashboard.png` — dashboard preview.

## Skills Demonstrated

Power BI, DAX, data analysis, KPI development, operational analytics, customer support analytics, trend analysis, performance reporting, and business recommendations.
