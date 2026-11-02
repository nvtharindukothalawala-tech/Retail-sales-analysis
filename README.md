\# Retail Sales Data Analysis



Mini project for the Data Analyst Intern assignment at Infinite Business Ventures (Pvt) Ltd.

The project cleans a retail sales dataset, analyzes it, creates charts, and builds an automated Excel report.



\## Files

| File | Description |

|---|---|

| `Retail\_Sales\_Analysis.ipynb` | Main notebook: cleaning, analysis, charts, Excel report, insights and management summary |

| `Retail\_Sales\_Intern\_Dataset.xlsx` | Raw data (never edited) |

| `Data\_Analyst\_Intern\_Assignment.pdf` | Assignment brief |

| `outputs/Cleaned\_Sales\_Data.csv` | Cleaned dataset (239 rows, with data-quality flags) |

| `outputs/Retail\_Sales\_Report.xlsx` | Generated Excel report (9 sheets) |

| `outputs/monthly\_sales\_trend.png` | Chart: monthly net sales |

| `outputs/brand\_net\_sales.png` | Chart: net sales by brand |

| `outputs/outlet\_net\_sales.png` | Chart: net sales by outlet |



\## How to run

1\. Install the tools: `pip install notebook pandas matplotlib openpyxl`

2\. Open the notebook: `jupyter notebook`

3\. Click \*\*Kernel → Restart \& Run All\*\*.

4\. The cleaned data, charts and Excel report are regenerated in the `outputs` folder. Close the Excel file before running.



\## Key cleaning decisions

\- Removed 1 duplicate row (INV-10018).

\- Standardised 1 brand text (" be desi" to "Be Desi").

\- Recalculated 1 missing net sales value from valid inputs (INV-10156).

\- Excluded 4 rows with invalid quantity, price or discount from the analysis. They stay in the Cleaned Data sheet with flags.

\- Flagged, but kept: 2 unknown brands, 1 unknown outlet, 1 missing date, 3 net sales mismatches.



\## Headline results

Total net sales LKR 5,286,353.50 | 727 units | 235 invoices | ATV LKR 22,495.12



\## AI disclosure

I used Claude (an AI assistant by Anthropic) for guidance on the approach and for help with code and explanations while learning. I have reviewed and understood each part, and I can explain and modify every part of this solution.

