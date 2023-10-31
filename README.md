# Report Creation Scripts

## Overview
Collection of scripts to create daily, monthly and summary machine utilization report in spreadsheet.
## Folder Structure
Below is the directory structure of the scripts for creating daily, monthly and summary machine utilization report in spreadsheet.
``` 
├── 003_Report_Creation
│   ├── input
│   ├── jre
│   │    ├── linux
│   │    └── windows
│   ├── lib
│   │    ├── classes
│   │    └── CsvToExcelReport.jar
│   ├── logs
│   ├── reports
│   ├── templates
│   ├── daily_report_creation.cmd
│   ├── daily_report_creation.sh
│   ├── monthly_report_creation.cmd
│   ├── monthly_report_creation.sh
│   ├── README.md
│   ├── summary_report_creation.cmd
│   └── summary_report_creation.sh

```
### Scripts Descriptions
* **<ins>daily_report_creation.sh</ins>**    - Use to create daily machine utilization report in spreadsheet.(**Linux**)
* **<ins>daily_report_creation.cmd</ins>**   - Use to create daily machine utilization report in spreadsheet.(**Windows**)
* **<ins>monthly_report_creation.sh</ins>**  - Use to create monthly machine utilization report in spreadsheet.(**Linux**)
* **<ins>monthly_report_creation.cmd</ins>** - Use to create monthly machine utilization report in spreadsheet.(**Windows**)
* **<ins>summary_report_creation.sh</ins>**  - Use to create summary machine utilization report in spreadsheet.(**Linux**)
* **<ins>summary_report_creation.cmd</ins>** - Use to create summary machine utilization report in spreadsheet.(**Windows**)

## Usage in Linux

    ./<script_name>.sh

## Usage in Windows

    <script_name>.cmd - Double click the file to run it.

## Before you begin

1. Copy the folder (003_Report_Creation) and (004_Report_Mailer) from main to desired location.
2. Make sure that \003_Report_Creation\input\ folder has file/s needed for creating reports.
3. Recipient of the email can be set in the application.properties file of the 005_email_sender folder.
See README.md in 004_Report_Mailer for further instructions.
