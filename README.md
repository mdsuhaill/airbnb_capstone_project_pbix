Airbnb Price & Scenario Analysis Dashboard

📌 Project Overview
This project presents an interactive Power BI dashboard built to analyse Airbnb listings in Antwerp. The dashboard helps property owners and stakeholders evaluate listing performance, price trends, and projected revenues under different scenarios — without relying on machine learning.

The solution enables users to:

Track average prices, availability, review counts, and projected revenue.

Explore scenario-based insights using What-If parameters for occupancy and seasonal multipliers.

Visualise listings through maps, price distributions, and trend charts.

Drill down into top-performing listings and review details.

🎯 Problem Statement
As defined in the project scope:

Develop a Power BI dashboard for Airbnb listings in Antwerp that provides self-service insights into listing performance and revenue projections. The dashboard should allow dynamic scenario analysis with interactive filters and “What-If” parameters.

🔑 Key Features

Data Ingestion & Cleaning

Connected Airbnb data sources (Calendar, Listings, Hosts, Reviews).

Standardised price fields, text attributes, and date formats.

Normalised host/review tables.

Data Modeling

Built a star schema linking Listings, Calendar, Hosts, and Reviews.

Aggregated metrics: average price, review counts, availability, projected revenue.

Scenario Analysis

Implemented What-If parameters for occupancy rates & seasonal multipliers.

Designed DAX measures for scenario-based pricing & revenue projections.

Dashboard Design (3 Pages)

Overview: KPI cards, slicers, overall insights.

Listing Analysis: Map of listings, price distribution histogram, top listings table.

Scenario Insights: Scenario-based comparisons, revenue trend lines, drill-through.

Interactivity

Drill-through reports, bookmarks, tooltips, and dynamic slicers.

Deployment & Documentation

Published to Power BI Service with scheduled refresh.

User guide with navigation, DAX formulas, and data model documentation.

📊 Dashboard Snapshots
Example KPIs from the dashboard:

Average Price: $109.92

Availability Rate: 53.52%

Total Listings: 1,749

Projected Revenue: $13.50M

👩‍💻 Tech Stack

Power BI Desktop & Service

DAX for measures and scenario calculations

Star Schema Data Modelling

Azure Maps Integration for geo-visualizations

🚀 How to Use

Open the .pbix file in Power BI Desktop.

Navigate through the three report pages (Overview → Listing Analysis → Scenario Insights).

Adjust the What-If parameters (Occupancy Rate & Seasonal Multiplier) to see real-time revenue impact.

Use slicers (Date, Property Type, Room Type) for interactive filtering.

👥 Contributors
This project was collaboratively developed by:

Chinta Dileep Chandra

Suhail

Vikranth Singh

Priyanka Gupta

Rohit Sharma

Nikitta Natraj

📂 Repository Structure
Capstone Project_CPDA_B3_Group1.pdf – Final Dashboard report
Problem_Statement.pdf – Project requirements
README.md – Project documentation
/pbix-file/ – Power BI .pbix file (if shared)

🏆 Outcome
A self-service Power BI solution empowering stakeholders to:

Analyze Airbnb listing trends.

Simulate revenue scenarios.

Make data-driven decisions based on real-time insights.
