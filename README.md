# Manufacturing Production & Quality Analytics Dashboard

## Project Overview
This project analyzes production and quality performance across two manufacturing plants (Kanpur and Bengaluru) using a synthetic dataset modeled on a real machine portfolio, including Nova 10, Nova 82, LSL, Circular Looms, Lofil Multifilament Lines, and TE-600 Tape Extrusion Lines. The analysis tracks production efficiency, downtime, defect rates, and delayed orders to surface actionable improvement areas for plant management.

## Objective
To build an end-to-end analytics solution that identifies the key drivers behind production inefficiency, machine downtime, and quality defects, and to translate those findings into clear, actionable recommendations.

## Tools & Technologies
- Power BI (DAX, Power Query, Key Influencers, Decomposition Tree)
- Excel (Power Pivot, PivotTables, Dynamic KPI Cards)

## Key Analysis Performed
- Data Cleaning & Transformation (Power Query)
- KPI Measure Development (DAX)
- Production Efficiency & OEE-style Analysis
- Defect Rate Analysis by Machine/Process
- Shift-wise and Plant-wise Performance Comparison
- Root-Cause Analysis via Key Influencers & Decomposition Tree
- Drill-Through Reporting for Detailed Investigation

## Dataset
10,000-row synthetic manufacturing dataset (2022–2024) covering production orders across the Kanpur and Bengaluru plants.

## KPI Summary (Overall, 2022–2024)
Metric                         Value 

Total Orders                    10,000
Total Units Produced            2,442,793
Average Downtime                1.95 hrs
Average Defect Rate             7.41%
Average Production Efficiency   66.31% 
Target Achievement              69.67% 
Delayed Orders                  9.77% 

## Key Findings
- Tape Winding has the highest defect rate among all processes (7.85%).
- Afternoon shift is the most efficient (66.57%); Night shift is the least efficient (65.58%).
- Roughly 10% of orders are delayed.
- The Prototype Circular Loom machine has the highest downtime.
- The Bengaluru plant is slightly more efficient than the Kanpur plant.

## Recommendations
- Prioritize preventive maintenance for Tape Winding machines to reduce defect rate.
- Investigate root causes behind Night shift underperformance.
- Address the root cause behind the 9.77% delayed-order rate to improve on-time delivery.

## Project Structure

Manufacturing_Production_Quality_Dashboard/
Data/
    manufacturing_data.csv       -> Source dataset
PowerBI/
    Manufacturing_Dashboard.pbix  -> Power BI dashboard file
Excel/
    Manufacturing_Dashboard.xlsx  -> Excel dashboard (Power Pivot)
Screenshots/
    (dashboard page images)
 README.md                         -> Project documentation


## Learning Outcomes
Through this project, the following skills were developed:
- DAX measure development (AVERAGEX, FILTER, CALCULATE, DIVIDE)
- Power Query data cleaning and transformation
- KPI dashboard design across multiple report pages
- Root-cause analysis using Key Influencers and Decomposition Tree visuals
- Cross-tool consistency between Power BI and Excel reporting

## Future Improvements
- Incorporate live/refreshed data instead of a static snapshot
- Add predictive maintenance modeling for high-downtime machines
- Extend analysis with Tableau for comparative visualization

## Author
Garima Darolia
