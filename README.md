🛫 US Flight Delay Analysis Dashboard (Power BI)
📘 Project Overview

This Power BI dashboard analyzes flight performance across major US airlines from 2019–2023, providing insights into delay patterns, cancellation trends, and operational efficiency.
The goal is to identify the main causes of delays, compare airline punctuality, and help decision-makers improve on-time performance and service reliability.

🎯 Objective

To design a data-driven Power BI dashboard that:

Tracks on-time performance (OTP) and average delays.

Identifies the main delay causes (Carrier, Weather, NAS, Security, Late Aircraft).

Compares airline-level performance metrics.

Highlights cancellation trends and delay distributions by time, airport, and route.

📊 Key Insights (2019–2023)

✈️ Total Flights: 1.05 million

⏱️ Average Arrival Delay: 4.14 minutes

🟢 On-Time Performance (OTP): 67.3%

🔴 Cancellation Rate: 2.63%

🌦️ Top Delay Reasons:

Carrier delays – 36.5%

Late aircraft – 37.8%

Weather – 5.8%

NAS (Air Traffic System) – 19.6%

Security – 0.2%

Airlines with Best OTP:

SkyWest (OO) – 71.0%

PSA Airlines (OH) – 68.5%

Mesa Airlines (YV) – 68.1%

Airlines with Highest Delays:

Allegiant Air (G4) – 12.8 min avg delay

JetBlue (B6) – 11.8 min avg delay

Frontier (F9) – 11.3 min avg delay

🧮 KPIs & Metrics

KPI	Description

Total Flights	Count of total flight records
Average Arrival Delay (min)	Mean of arrival delay minutes
On-Time % (OTP)	% of flights with arrival delay ≤ 15 min
Cancellation Rate %	% of total flights cancelled
Delay Breakdown %	Share of delay minutes by cause
Avg Delay by Airline / Airport	Compares airline and airport performance
Delay Trend (Monthly / Yearly)	Visualizes delay fluctuations over time
📈 Dashboard Pages
1️⃣ Overview Dashboard

KPIs: Total Flights, Avg Delay, OTP %, Cancellation Rate %

Yearly trend: OTP vs Cancellation Rate

Delay cause breakdown (Carrier, Weather, NAS, etc.)

Map visualization by Origin Airport

2️⃣ Airline Performance

Average Arrival Delay by Airline

On-Time % and Total Flights per Airline

Delay causes stacked comparison

3️⃣ Delay Reason Analysis

Pie chart: Delay % by reason

Total delay minutes by airline & cause

Cancellation codes by frequency

🧠 Technical Implementation
Component	Description
Tool	Microsoft Power BI Desktop
Data Source	US Bureau of Transportation Statistics (2019–2023)
Data Volume	1M+ records
Data Cleaning	Power Query (null handling, conditional logic, standardization)
Data Modeling	Star Schema – Fact (Flights), Dim (Date, Airline, Airport)
Measures Used	DAX: SUM, AVERAGE, DIVIDE, CALCULATE, SAMEPERIODLASTYEAR
Interactivity	Drill-through, slicers (Year, Airline, Airport), tooltips, bookmarks

💡 Key Learnings

Optimized large datasets using Power Query transformations and DAX measures.

Designed dynamic KPI cards, hierarchical slicers, and interactive visuals.

Gained experience in data modeling (Star Schema) and performance tuning in Power BI.

Enhanced storytelling through data-driven visuals and trend analysis.

🖼️ Dashboard Preview

<img width="1314" height="736" alt="Airlines Delays Page 1" src="https://github.com/user-attachments/assets/1382a4bd-a12d-43f0-b92b-2bfecdf65bd7" />
<img width="1308" height="797" alt="Airlines Delays Page 2" src="https://github.com/user-attachments/assets/5d89e674-7958-451d-922a-76a806128a37" />


📂 Repository Structure
📁 US-Flight-Delay-Dashboard
│
├── 📊 PowerBI_Project.pbix
├── 📄 README.md
├── 📁 Dataset/
│   └── flight_delay_data.csv
├── 📁 Images/
│   ├── overview.png
│   ├── airline_performance.png
│   └── delay_reason.png


🧰 Tools & Technologies

Power BI Desktop

Power Query (M Language)

DAX (Data Analysis Expressions)

Excel / CSV

Data Visualization & Storytelling

🧾 Author

Vishal Maheshwary
