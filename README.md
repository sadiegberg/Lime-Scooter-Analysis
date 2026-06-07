# Lime Scooter Demand Analysis — Austin, TX (2022)

# Project Overview

This project analyzes shared micromobility trip data from Austin, Texas to answer the question:

What factors influence Lime scooter demand, and how can trip patterns inform smarter fleet deployment decisions?
Understanding when and why riders use scooters is a real operational challenge for companies like Lime. Too few scooters in the wrong place means lost revenue. Too many means unnecessary rebalancing costs. This analysis identifies the key demand drivers using publicly available city data.

# Data Source

Dataset: Shared Micromobility Vehicle Trips (2022)
Source: City of Austin Open Data Portal
Rows analyzed: 828,506 scooter trips
Tools used: Python, pandas, matplotlib, Jupyter Notebook
Key Findings

Finding 1: Demand Peaks During Commute Hours

Rides spike sharply at 8am and 4–6pm, matching classic commuter patterns. Overnight hours (12am–5am) see minimal activity. This strongly suggests a large portion of Lime’s Austin ridership uses scooters as a last-mile commute solution.

Finding 2: Weekday Usage Dominates

Demand is consistently higher on weekdays than weekends. This reinforces the commuter-use pattern — riders are primarily using scooters to get to and from work, not for weekend leisure.

Finding 3: Spring and Fall Are Peak Seasons

Ridership peaks in March–May and September–October, with a notable dip in summer. Austin’s extreme heat likely discourages outdoor riding in June–August, creating a predictable seasonal demand curve.

# Business Implications

Finding	Recommendation
Commute-hour spikes	Maximize fleet availability near transit hubs before 8am and 4pm
Weekday dominance	Focus rebalancing resources on Monday–Friday operations
Seasonal dip in summer	Reduce operational overhead in June–August; ramp up marketing in spring and fall
Project Structure

lime-scooter-analysis/
│
├── README.md                  ← You are here
└── analysis.ipynb             ← Full Jupyter Notebook with code and findings
 
--- 

This project was built as part of a data analytics portfolio to demonstrate skills in data cleaning, exploratory analysis, and business-oriented storytelling with real-world data.
