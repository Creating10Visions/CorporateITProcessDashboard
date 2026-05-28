# Corporate IT Process Dashboard
# Programmer: Vanessa Pickens

## Overview
This project is a mock IT process analysis tool built to track requests, measure workflow performance, and generate KPI reports. 
It uses Python, SQLite, and CSV data to simulate process improvement reporting for an IT operations environment.

## Purpose
The goal of this project is to demonstrate how process data can be collected, analyzed, and reported to support better decision-making, 
improved workflow visibility, and continuous improvement.

## Features
- Imports mock IT request data from a CSV file
- Stores records in a SQLite database
- Calculates KPIs such as total requests, open requests, completed requests, blocked requests, overdue requests, and average cycle time
- Generates summary charts for requests by status and requests by team
- Saves chart images in the Output/charts folder

## Tools Used
- Python
- SQLite
- CSV
- Matplotlib

## Project Files
- `Scripts/import_data.py` – imports mock request data into SQLite
- `Scripts/kpi_report.py` – generates KPI summary output
- `Scripts/chart_report.py` – creates chart visualizations
- `Data/it_requests.csv` – mock request data
- `Output/it_process.db` – SQLite database
- `Output/kpi_summary.txt` – KPI summary report
- `Output/charts/` – generated chart images

## How to Run
1. Run `import_data.py` to create the database and load the CSV data.
2. Run `kpi_report.py` to generate the KPI summary report.
3. Run `chart_report.py` to create the charts.

## Notes
This project uses synthetic mock data only and does not contain any real company or employee information.

## Run the Full Dashboard

Run the following command to execute the complete dashboard workflow:

```bash
python Scripts/run_all.py