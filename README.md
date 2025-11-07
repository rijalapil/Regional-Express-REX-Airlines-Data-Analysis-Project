# ✈️ Regional Express (REX) Airlines Data Analysis Project

## 📘 Project Overview

This project presents a complete data analytics case study for Regional Express (REX) Airlines, an Australian domestic airline operating mainly across Eastern and South-Eastern Australia. REX connects regional towns and cities such as Wagga Wagga, Dubbo, Armidale, and Mildura with major hubs like Sydney, Melbourne, and Adelaide.

The dataset was synthetically generated to closely resemble real-world operational and commercial data, capturing how REX manages its flight schedules, delays, load factors, and fare performance.
This end-to-end analysis demonstrates how data-driven insights can enhance airline operations, passenger experience, and profitability.

## 🎯 Project Objectives

Understand flight punctuality and operational efficiency across REX’s regional network.

Analyze passenger load factors and aircraft utilization rates for domestic routes.

Evaluate fare structures and revenue performance across different classes and routes.

Visualize business KPIs using dashboards built in Power BI and Tableau.

Propose data-backed recommendations for improving REX’s route and service strategies.

## 🧾 Dataset Overview

File name: rex_airlines_dataset.csv
Rows: 32,000 Columns: 22
Scope: Domestic routes in NSW, VIC, SA, QLD, and TAS
Note: Synthetic dataset generated with realistic airline statistics.

Column	Description
flight_id	Unique flight identifier
flight_date	Flight date
airline	“Regional Express”
origin_airport, dest_airport	Departure and arrival airport codes
origin_city, dest_city	Associated cities
aircraft_type	Saab 340B or Boeing 737-800
capacity	Aircraft seating capacity
passengers	Number of passengers
load_factor	Occupancy rate per flight
distance_km	Distance between origin and destination
scheduled_dep_time, scheduled_arr_time	Scheduled times
actual_dep_time, actual_arr_time	Actual times (if completed)
dep_delay_min, arr_delay_min	Delay durations in minutes
fare_class	Saver / Flex / Business
fare_price_aud	Average fare in AUD
baggage_kg_total, cargo_kg_total	Weight carried
status	Completed / Cancelled
cancellation_reason	Reason if cancelled

## 🧰 Tools and Technologies
Category	Tools Used
Data Processing	Python (Pandas, NumPy, Scikit-Learn)
Database	MySQL / PostgreSQL
Visualization	Power BI, Tableau, Matplotlib, Seaborn
Automation	Flask / FastAPI (for API integration)
Environment	Jupyter Notebook / VS Code
Version Control	Git / GitHub

## 📊 Dashboards and Visualizations
### 1. Flight Operations Dashboard

Visualizes the total flights, average delay, and route network density.
📸 Placeholder for Power BI or Tableau screenshot
![Operations Dashboard](assets/operations_dashboard.png)

### 2. Punctuality & Delay Insights

Analyzes departure and arrival delays by airport, route, and aircraft type.
📸 Placeholder for delay analysis chart
![Delay Dashboard](assets/delay_dashboard.png)

### 3. Revenue and Fare Performance

Shows revenue by fare class, average price per kilometer, and occupancy rates.
📸 Placeholder for revenue visualization
![Revenue Dashboard](assets/revenue_dashboard.png)

### 4. Cancellations and Reliability

Explores patterns in flight cancellations and identifies operational risk areas.
📸 Placeholder for cancellation breakdown chart
![Cancellations Dashboard](assets/cancellations_dashboard.png)

## 📈 Analysis Highlights

### On-Time Performance:
Average departure delay: ~7 minutes. Weather and crew availability are key delay factors.

### Load Factor Insights:
Saab 340B flights operate at ~68 % load on regional routes; Boeing 737 flights on major routes average ~76 %.

### Fare and Revenue Patterns:
Business class makes up only 10 % of seats but contributes 25 % of fare revenue.

### Cancellation Trends:
60 % of cancellations are weather-related, most frequent in winter months across regional NSW.

### Recommendations:

Increase Boeing 737 frequency on high-demand routes (SYD–MEL, SYD–ADL).

Optimize Saab 340B routes with low load factors through scheduling or fare adjustments.

Invest in predictive maintenance and crew scheduling analytics.

## 🧠 Future Analytical Extensions

Predict flight delays based on route, aircraft, and season.

Build revenue forecasting models using fare and occupancy data.

Develop route profitability dashboards with dynamic what-if simulations.

## 🗂️ Repository Structure
rex-airlines-analysis/

├── data/
    └── rex_airlines_dataset.csv

├── notebooks/
    ├── 01_data_cleaning.ipynb
    ├── 02_exploratory_analysis.ipynb
    ├── 03_dashboard_visualizations.ipynb
    └── 04_predictive_modelling.ipynb

├── assets/
    ├── rex_airlines_banner.jpg
    ├── operations_dashboard.png
    ├── delay_dashboard.png
    ├── revenue_dashboard.png
    └── cancellations_dashboard.png

├── reports/
    └── REX_Airlines_Analysis_Report.pdf

└── README.md

## 🚀 How to Run

### Clone the repository

git clone https://github.com/yourusername/rex-airlines-analysis.git
cd rex-airlines-analysis


### Install dependencies

pip install -r requirements.txt


### Open Jupyter Notebook

jupyter notebook notebooks/01_data_cleaning.ipynb


### View Dashboards

Power BI: dashboards/rex_dashboard.pbix

Tableau: dashboards/rex_dashboard.twbx

## 👨‍💻 Author

Aaron Rijal
📍 Oak Park, VIC, Australia
📧 aaronrijal43@gmail.com

🔗 LinkedIn

## ⭐ Project Summary

This project demonstrates practical data analytics and visualization skills through an aviation-based business scenario.
By leveraging real-world logic in a synthetic dataset, it showcases data storytelling, business analysis, and predictive modelling within the context of the Australian domestic airline industry.
