✈️ Flight Delay & Performance Analysis Dashboard
📌 Project Overview

This project analyzes flight delay patterns and performance using interactive Tableau dashboards.
The goal is to understand when delays happen, which airlines and routes are most affected, and how distance impacts delays, enabling better operational decision-making.

The project consists of two dashboards:

Time Performance Dashboard

Airline & Route Performance Dashboard

🎯 Business Problem

Flight delays impact:

Passenger satisfaction

Airline operational costs

Airport efficiency

However, delays are influenced by multiple factors such as time of day, airline operations, route traffic, and distance.
This project helps stakeholders identify delay patterns and focus improvement efforts.

🧩 Dashboards Included
1️⃣ Time Performance Dashboard

Focuses on time-based delay analysis.

KPIs

Total Flights

Delayed Flights

% Delayed Flights

Charts

Average Departure Delay by Hour (Line Chart)

% Delayed Flights by Hour (Area Chart)

Delayed vs On-Time Flights by Hour (Stacked Bar)

Delay Frequency Distribution (Histogram)

Key Insights

Delays peak during afternoon and evening hours

Most delays are short (under 30 minutes)

Long delays are rare but impactful

2️⃣ Airline & Route Performance Dashboard

Focuses on airline, route, and distance-based analysis.

KPIs

Total Routes

Average Delay (minutes)

Charts

Total Flights by Airline (Bar Chart)

Share of Delayed Flights by Airline (Tree Map)

Distance vs Average Departure Delay (Scatter Plot)

Total Flights by Route (Horizontal Bar Chart)

Key Insights

Delay performance varies significantly by airline

High-traffic routes contribute most to operational impact

Distance alone does not determine delays

🔎 Filters & Interactivity

Filters

Flight Date (Range)

Airline Name (Multi-select)

Distance Category (Short / Medium / Long Haul)

Parameter

Delay Threshold (Minutes)

Dynamically defines what counts as a delay

Applied only to delay-based charts

Interactions

Cross-filtering between visuals

Hover tooltips for detailed insights

Dashboard-level consistency across filters

🧮 Key Calculations
Calculation	Description
Delayed Flights	Flights with delay > threshold
% Delayed Flights	Ratio of delayed flights
Average Delay	Average departure delay (minutes)
Total Routes	Distinct origin–destination pairs
📂 Dataset Information

Source: Flight performance dataset

Format: CSV

Key Fields:
flight, airline_name, origin, dest, distance,
dep_delay, arr_delay, time_hour, flight_date, distance_category

🛠 Tools Used

Tableau Public

CSV Dataset

Data Cleaning & Calculations in Tableau

🚀 Project Outcome

This project demonstrates:

Strong understanding of business KPIs

Effective dashboard storytelling

Proper use of filters, parameters, and calculations

Clear separation of volume vs delay analysis

👤 Author

Afna Jasmin A T
Aspiring Data Analyst | Tableau | SQL | Excel | Data Visualization# TABLEAU-PRO
