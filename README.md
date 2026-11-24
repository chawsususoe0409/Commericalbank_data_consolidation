# Commericalbank_data_consolidation
Bank of Thailand 1997 - 2025 accounting data consolidate
Commercial Bank Data Consolidation Using Python

📌 Project Overview

This project automates the consolidation of multiple Commercial Bank Excel reports into a single structured dataset using Python.

Instead of manually combining data from multiple Excel files, this project uses Python, Pandas, and Excel processing techniques to automate data extraction, transformation, consolidation, and reporting.

The objective is to reduce manual work, improve data consistency, and prepare consolidated data for further analysis.

🎯 Project Objectives

Automate the processing of multiple Excel files.

Extract relevant banking data from Excel reports.

Transform monthly data from columns into rows.

Standardize Month, Year, and Amount data types.

Consolidate data from multiple source files.

Generate a summary report using a Pivot Table.

🛠️ Technologies Used

Python

Pandas – Data manipulation and consolidation

OpenPyXL – Excel file processing

OS – File and folder management

pathlib – File path handling

tqdm – Progress bar for processing multiple files

Jupyter Notebook – Development environment

📂 Project Workflow

Import Libraries
Import the required Python libraries.

Set Source Folder
Define the folder containing multiple Commercial Bank Excel files.

Read Excel Files
Loop through all files in the source folder and read Excel data, skipping the first five rows.

Data Cleaning
Rename unnamed columns and identify the last relevant data row using the "No. of banks" marker.

Data Transformation
Convert monthly columns into a row-based structure containing:

Item No.

Account

Amount

Month

Year

Data Standardization
Convert month names into numeric months and standardize Year and Amount data types.

Data Consolidation
Combine all processed files into one consolidated DataFrame.

Excel Export
Export the consolidated dataset and Pivot Table into separate Excel files.

📊 Output Files

The project generates two Excel files:

Output File

Description

ChawSuSuSoe_Final_Commercial_Bank_Consolidated.xlsx

Consolidated data from all source Excel files

ChawSuSuSoe_Final_Commercial_Bank_ConsolidatedPivot.xlsx

Summary of total Amount by Source File, including Grand Total

📁 Expected Input Structure

Place all source Excel files in one folder.

Project/
│
├── FinalCapstoneProject.ipynb
│
├── Data/
│   ├── Bank_Report_01.xlsx
│   ├── Bank_Report_02.xlsx
│   ├── Bank_Report_03.xlsx
│   └── ...
│
└── Output/
    ├── Consolidated.xlsx
    └── ConsolidatedPivot.xlsx

⚙️ Installation and Requirements

Install the required Python libraries:

pip install pandas openpyxl tqdm

🚀 How to Run

Clone or download this repository.

Install the required libraries.

Prepare the source Excel files in a folder.

Update the source folder path in the Jupyter Notebook.

Run all notebook cells sequentially.

Check the generated Excel output files.

💡 Key Learning Outcomes

Through this project, I practiced:

Python file handling and directory management.

Reading and processing multiple Excel files.

Using loops for repetitive data processing.

Data cleaning and transformation with Pandas.

Converting wide-format data into long-format data.

Data type conversion and standardization.

Combining datasets using pd.concat().

Generating Pivot Tables for summary reporting.

Exporting processed data into Excel.

👩‍💻 Author

Chaw Su Su Soe

Python Data Analysis | Excel Automation | Data Processing

This project was developed as part of my Python Data Analysis Capstone Project.
