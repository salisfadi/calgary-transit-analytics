# Calgary Transit Fleet Analytics

An independent analytics project exploring Calgary Transit's fleet, ridership,
and emissions data using the City of Calgary's open data portal
(data.calgary.ca).

## Why This Project

Public transit agencies manage large vehicle fleets where reliability,
utilization, and environmental impact directly affect service quality and
cost. I wanted to understand these dynamics using real, publicly available
data: How well is the fleet matched to ridership demand? What can we learn
about reliability and state of repair from available records? How is the
fleet's environmental footprint trending as electrification rolls out?

This project walks through the full analytics lifecycle — from raw data
to a decision-ready dashboard and report — the way an analyst would
approach it on the job.

## What This Project Covers

- Data extraction, cleaning, and quality auditing
- Fleet utilization and reliability analysis
- Greenhouse gas emissions tracking
- Time-series forecasting
- Interactive dashboards (Power BI) and automated reports (Excel)
- Business case development with actionable recommendations

## Data Sources

| Dataset                    | Source          | Update Frequency |
| -------------------------- | --------------- | ---------------- |
| Calgary Transit Fleet List | data.calgary.ca | Weekly           |
| Calgary Transit Ridership  | data.calgary.ca | Monthly          |
| Calgary Transit Routes     | data.calgary.ca | As needed        |

## Project Structure

calgary-transit-analytics/
├── data/
│ ├── raw/ # Original data as downloaded — never modified
│ └── processed/ # Cleaned and transformed data ready for analysis
├── notebooks/ # Jupyter notebooks, one per analysis phase
├── sql/ # Database schema and analysis queries
├── scripts/ # Reusable Python scripts
├── reports/ # Excel templates and Word documents
├── dashboard/ # Power BI files
└── docs/ # Data dictionary, methodology, and user guides

## How to Run This Project

git clone https://github.com/salisfadi/calgary-transit-analytics.git
cd calgary-transit-analytics

python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt

jupyter notebook

## Author

**Sali Alsafadi**
MSc Software Engineering

## Status

Phase 1 In Progress — Data Foundation
