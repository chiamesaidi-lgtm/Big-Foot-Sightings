Kentucky Bigfoot Sightings — Tableau Portfolio Project

<p align="center">
  <img src="https://img.shields.io/badge/Tableau-Data%20Visualization-1F77B4?style=for-the-badge&logo=tableau&logoColor=white">
  <img src="https://img.shields.io/badge/Data%20Analytics-Portfolio-20352A?style=for-the-badge">
  <img src="https://img.shields.io/badge/Kentucky-99%20Sightings-52796F?style=for-the-badge">
</p>

📌 Project Overview

This portfolio project analyzes reported Bigfoot sightings in Kentucky using a sightings dataset containing 4,642 records, with 99 Kentucky records.

The project focuses on identifying patterns in reported sightings across time, seasons, months, and report classifications.

Important: The analysis describes reports contained in the dataset. It does not establish the existence of Bigfoot.

🎯 Objectives

Analyze reported Kentucky sightings over time.

Identify seasonal patterns.

Identify months with higher reporting activity.

Compare report classifications.

Build an interactive Tableau dashboard.

Practice calculated fields, filters, KPIs, and visual storytelling.

📊 Dashboard Worksheets

The planned Tableau dashboard contains:

KPI — Total Kentucky Sightings

KPI — Class A Sightings

KPI — Peak Reporting Year

Sightings Over Time

Sightings by Season

Sightings by Month

Sightings by Classification

Kentucky vs. Other States

🎛️ Interactive Filters

Recommended dashboard filters:

Year

Season

Month

Class

Report Type

🧮 Tableau Calculated Fields

Kentucky Flag

IF [State] = "Kentucky"
THEN "Kentucky"
ELSE "Other"
END

Class A Sightings

IF [Class] = "Class A"
THEN 1
ELSE 0
END

Class B Sightings

IF [Class] = "Class B"
THEN 1
ELSE 0
END

Month Number

CASE [Month]
WHEN "January" THEN 1
WHEN "February" THEN 2
WHEN "March" THEN 3
WHEN "April" THEN 4
WHEN "May" THEN 5
WHEN "June" THEN 6
WHEN "July" THEN 7
WHEN "August" THEN 8
WHEN "September" THEN 9
WHEN "October" THEN 10
WHEN "November" THEN 11
WHEN "December" THEN 12
ELSE 13
END

🔎 Initial Dataset Findings

Based on the Kentucky subset:

99 reported sightings

59 Class A reports

39 Class B reports

1 Class C report

Fall has the highest number of reports.

October is the most frequently reported month.

Kentucky records span approximately 1950–2018.

🛠️ Skills Demonstrated

Tableau dashboard design

Data visualization

Calculated fields

Filters and parameters

KPI development

Time-series analysis

Categorical analysis

Data storytelling

Business/research question formulation

📁 Repository Structure

kentucky-bigfoot-sightings/
│
├── README.md
├── Kentucky_Bigfoot_Sightings_Dashboard.xlsx
├── data/
│   └── sightings.csv
└── tableau/
    └── Kentucky_Bigfoot_Sightings.twbx

🚀 Future Improvements

Add a geographic map of sightings.

Add a year-range parameter.

Add state-level comparison.

Add tooltip-based storytelling.

Publish the finished dashboard to Tableau Public.

Add a direct Tableau Public link to this README.

👤 Author

G.M. CHIA

Data Analytics Portfolio Project
