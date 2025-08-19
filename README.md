# TheBounds-Dashboard-Placement-2025

The Bounds Dashboard Project - MSc Health Data Science Placement 2025

**Project overview** \n
This repository contains my work for the MSc Health Data Science professional placement at The Bounds Counselling and Research Centre, University of Aberdeen (June–August 2025).
The project focuses on developing a Centralised Operational Dashboard in Power BI to support:
- Client intake and allocation workflows
- Counsellor matching (based on risk, preferences, availability)
- Monitoring of waiting lists, room usage, and service demand trends
The dashboard uses mock data (based on the structure of intake forms and appointment records) to simulate real-world scenarios, due to confidentiality restrictions.

**Methods**
- Data Simulation: Created mock datasets (normal distributions for CORE-10, PHQ-9, GAD-7; random assignment of client preferences and counsellor types).
- Dashboard Development: Built dashboards in Power BI with interactive filters, counsellor allocation logic, and heatmaps for room usage.

**Outputs**
- Services Dashboard: Overview of client demand, waiting lists, and service categories (F2F, Online, CYP).
- Client-Counsellor Matching Dashboard: Supports allocation decisions by matching client needs with counsellor skills, experience, and availability.
- Booking Heatmap: Visualises room and time-slot utilisation from calendar data.

**Data confidentiality** \n
No real client data is included in this repository.
All datasets are mock data, designed to mirror the structure and variables of real data (e.g., intake form responses, waiting list formats, booking calendars).

**How to use**
- Clone/download this repository.
- Open .pbix files in Power BI Desktop.
- Load mock data from /data folder to replicate dashboards.

**Version control**
- This repository is developed with version control best practices:
- Regular commits with meaningful messages.
- Separate folders for data, scripts, and dashboards.
- Iterative versions of dashboards (tagged releases: v1.0, v2.0, etc.).

**Acknowledgements** \n
Placement host: The Bounds, Counselling and Research Centre \n
MSc Health Data Science, University of Aberdeen \n
Mock data sources inspired by PsyToolkit, open-access Kaggle datasets, and statistical simulation methods.
