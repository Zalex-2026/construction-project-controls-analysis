# Construction Project Controls Analysis

## Overview

This project demonstrates the application of Python and data analysis techniques to construction project controls. It uses an illustrative Bill of Quantities (BOQ) dataset to evaluate cost performance, work-item progress, and project performance indicators.

The project combines construction engineering knowledge with Python-based data analysis to support more structured and transparent project monitoring.

## Objectives

- Analyze BOQ quantities, unit rates, and work-item values.
- Calculate earned value and compare it with actual expenditure.
- Identify work items with unfavorable cost variances.
- Calculate key project performance indicators.
- Visualize cost variance using Python.
- Export analyzed data to CSV for further reporting.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub
- CSV data processing

## Key Performance Indicators

| Indicator | Description |
|---|---|
| Budget at Completion (BAC) | Total approved BOQ budget used in this illustrative analysis |
| Earned Value (EV) | Budgeted value of completed work |
| Actual Cost (AC) | Actual expenditure recorded for the work |
| Planned Value (PV) | Budgeted value of work planned |
| Cost Performance Index (CPI) | EV divided by AC |
| Schedule Performance Index (SPI) | EV divided by PV |
| Estimate at Completion (EAC) | Forecast final cost based on current cost performance |
| Variance at Completion (VAC) | BAC minus EAC |

## Project Files

- `construction_project_Control_Analysis.ipynb` — Python notebook containing data preparation, calculations, and visualization.
- `construction_cost_analysis.csv` — analyzed construction data, including cost variances.
- `README.md` — project documentation.

## Illustrative Results

The analysis produces the following results:

- Total BOQ budget: 4,989,000 currency units
- Earned Value (EV): 4,410,500 currency units
- Actual expenditure (AC): 4,503,000 currency units
- Cost Performance Index (CPI): approximately 0.98
- Schedule Performance Index (SPI): approximately 0.98
- Estimate at Completion (EAC): approximately 5,093,633 currency units
- Variance at Completion (VAC): approximately −104,633 currency units

The results indicate that recorded expenditure exceeds earned value, while earned value is slightly below planned value. Under the stated EAC forecasting assumption, the projected final cost is above the original budget.

## Methodology

The analysis uses Pandas to organize the BOQ dataset, calculate work-item values, derive cost variances, and summarize project performance. Matplotlib is used to visualize cost variance across work items. The resulting analysis is exported to CSV for reuse.

## Data Disclaimer

The dataset is illustrative and intended for learning and portfolio demonstration. It should not be interpreted as verified financial information from an actual construction project. Monetary amounts are expressed in unspecified currency units.

## Author

**Alemayehu Tadesse Deyasso**

Construction Project Management | Cost Control | BOQ Analysis | Python-Based Engineering Analytics

This project reflects an ongoing effort to integrate construction engineering experience with data-driven project monitoring and decision support.
