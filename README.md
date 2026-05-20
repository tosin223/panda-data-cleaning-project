# Customer Data Cleaning Using Python (Pandas)

## Project Overview
This project focuses on cleaning and preparing a raw customer contact dataset for analysis and business use. The dataset contained duplicate records, inconsistent phone number formats, missing values, unnecessary columns, messy text fields, and customers who should not be contacted.

The goal was to transform the raw dataset into a clean, structured, and analysis-ready customer list.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Key Data Cleaning Steps
- Imported customer data from an Excel file using Pandas
- Removed duplicate customer records
- Dropped irrelevant columns that were not useful for analysis
- Cleaned customer names by removing unwanted characters
- Standardised phone numbers into a consistent format
- Replaced missing or invalid values such as `N/a` and blank entries
- Extracted address information into separate fields such as street, state, and zip code
- Standardised categorical values such as `Yes/No` into `Y/N`
- Filtered out customers marked as “Do Not Contact”
- Removed records with missing phone numbers
- Reset the final dataset index after cleaning

## Business Problem
Businesses often rely on customer contact lists for marketing, sales, and communication. However, messy or incomplete customer data can lead to poor decision-making, failed communication, and inefficient business operations.

This project demonstrates how Python can be used to clean raw customer data and prepare it for practical business use.

## Final Output
The final dataset contains only cleaned, contactable customer records with consistent formatting and structured fields, making it suitable for further analysis, reporting, or customer outreach.

## Skills Demonstrated
- Data cleaning
- Data transformation
- Missing value handling
- Text cleaning
- Data standardisation
- Feature extraction
- Business-rule filtering
- Pandas workflow

## Project Files
- `Data Cleaning in Pandas.ipynb` — Jupyter Notebook containing the full cleaning process
