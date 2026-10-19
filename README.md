# Public School Performance and Attendance Dashboard

A Power BI project for exploring student attendance, academic performance, and school fee records.

## Project overview
The dashboard project is intended to help educators and school administrators review attendance, subject-wise marks, overall academic performance, and fee-payment status in one place.

## Objectives
- Monitor student attendance percentages.
- Compare marks in Mathematics, English, and Science.
- Review average marks, grades, and pass/fail outcomes.
- Examine fee status, amounts paid, and outstanding balances.
- Make it easier to identify records that may need follow-up.

## Repository structure
```text
Public_School_Performance_Attendance_Dashboard/
├── 01_Dataset/
│   ├── Public_School_Performance_Dataset.xlsx
│   ├── student_data.csv
│   └── fee_structure.csv
├── 02_PowerBI_Dashboard/
│   └── Public_School_Performance_Dashboard.pbix
├── 03_Project_Presentation/
│   └── Project_Presentation.pptx
├── 04_Documentation/
│   └── data_dictionary.md
├── .gitignore
└── README.md
```

## Dataset
The Excel workbook contains two worksheets:

### `Student_Data` — 2,000 rows, 15 columns
Includes student ID, class, section, gender, attendance percentage, subject marks, average marks, grade, pass/fail status, and fee status/amount fields.

### `Fee_Structure` — 2,000 rows, 17 columns
Includes student ID, class, section, fee components, total fee, payment status, amount paid, balance, payment mode, installment plan, and last payment date.

CSV copies of both worksheets are provided for convenience. The Excel workbook is retained as the source dataset.

## Open the Power BI report
1. Download or clone this repository.
2. Open `02_PowerBI_Dashboard/Public_School_Performance_Dashboard.pbix` in Microsoft Power BI Desktop.
3. If Power BI requests a data source location, point it to the dataset included in `01_Dataset`.
4. Refresh the report and review the visuals and filters.

> Note: If the PBIX uses a local file path from the original computer, you may need to update the data source path in Power BI Desktop before refreshing.

## Tools
- Microsoft Power BI Desktop
- Microsoft Excel / CSV
- Python and pandas (used here to export worksheet copies to CSV)

## Project presentation
The project presentation is included in `03_Project_Presentation/Project_Presentation.pptx`.

## Data and privacy
Check the dataset for personal or sensitive information before publishing the repository publicly. If the data is not synthetic or approved for public sharing, use a sanitized copy instead.
