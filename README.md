# data-cleaning-excel-customer-records
Data cleaning and standardization project using Excel to transform messy, unstructured customer records into a clean, analysis-ready dataset.


🔷 Data Cleaning & Standardization in Excel
📌 Overview

This project demonstrates how to transform messy, unstructured customer data into a clean, structured, and analysis-ready dataset using Microsoft Excel.

Raw datasets often contain inconsistencies that make analysis difficult. In this project, I built a simple but effective data cleaning pipeline to improve data quality and usability.

🎯 Objectives
Convert unstructured data into a structured table
Standardize text formatting
Clean and format phone numbers
Ensure consistency across all records
Prepare data for analytics and reporting

📂 Dataset
🔹 Raw Data Issues:
Mixed casing (e.g., sMith, JACk)
Combined fields (names + phone numbers in one line)
Unformatted phone numbers
Inconsistent state abbreviations (ny, co, ME)
Extra spaces and irregular formatting

⚙️ Methodology
1. Data Parsing
Extracted names, phone numbers, and states from raw strings
Split full names into First Name and Last Name

3. Data Cleaning
Removed extra spaces using TRIM
Standardized casing using:
PROPER()
UPPER()
LOWER()

5. Data Transformation
Formatted phone numbers into:
+1 (XXX)-XXX-XXX
   
7. Data Structuring
Organized cleaned data into columns:
First Name
Last Name
Phone Number
State

🛠️ Tools Used
Microsoft Excel
Excel Functions (TRIM, PROPER, UPPER)

📊 Results
Created a clean, structured dataset
Improved data consistency and readability
Enabled easy analysis and visualization
Reduced potential errors in downstream analytics

🧠 Key Skills Demonstrated
Data Cleaning & Wrangling
Data Transformation
Data Quality Management
Excel for Data Analysis
Analytical Thinking
