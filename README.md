# Data-ANALYST
Marketing Campaign Data Cleaning Project
📂 Project Overview

This project involves cleaning and preprocessing the Marketing Campaign dataset to prepare it for analysis. The dataset contained missing values, duplicates, inconsistent formats, and irregular categorical data.

Objective:
Handle missing values
Remove duplicates
Standardize text fields
Convert dates and fix data types

📁 Dataset
Original Dataset: marketing_campaign.csv
Cleaned Dataset: marketing_campaign_cleaned.csv

📋 Steps Taken
Load Data – Imported CSV using Pandas and explored the structure (shape, head(), info()).
Handle Missing Values – Filled missing Income values with mean.
Remove Duplicates – Checked and removed any duplicated rows.
Standardize Text – Cleaned marital_status and other categorical fields (Absurd, YOLO, Alone → Single).
Fix Column Names – Converted to lowercase, stripped spaces, replaced spaces with underscores.
Convert Dates – Converted dt_customer to datetime type.

Data Type Correction – Ensured numeric columns were correctly typed.

Save Cleaned Dataset – Exported as marketing_campaign_cleaned.csv
