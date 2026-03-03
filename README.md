📂 Dataset Description
📁 File Structure

This project uses 12 CSV files in total:

4 Inpatient files

4 Outpatient files

4 Additional supporting files

1 Specialty Mapping file (used for dashboard enhancement)

All files were imported into Power BI and combined using Power Query.

🏥 Inpatient Files

The inpatient CSV files contain historical records of patients admitted to the hospital. These files include:

Admission dates

Waiting list size

Treatment categories

Time bands

Case types

Monthly performance data

These files were appended to create a consolidated inpatient dataset for analysis.

🏥 Outpatient Files

The outpatient CSV files include records of patients waiting for consultations or non-admission treatments. These datasets contain:

Referral dates

Waiting list volumes

Age profile distribution

Time band classification

Monthly breakdown

These files were also appended and transformed into a unified outpatient dataset.

🗺 Specialty Mapping File

A separate Specialty Mapping CSV file was used to enhance the dashboard functionality.

This file:

Maps department/specialty codes to readable specialty names

Standardizes specialty categorization

Enables specialty-level filtering and analysis

This mapping table was connected through relationships in the data model to allow users to:

View waiting lists by medical specialty

Compare specialty-level performance

Filter KPIs based on department

This significantly improved dashboard interactivity and analytical depth.

📊 Dashboard Overview
🎯 Purpose of the Dashboard

The dashboard provides a comprehensive overview of hospital waiting list performance across inpatient and outpatient services.

It allows stakeholders to:

Monitor total waiting list volumes

Track monthly performance trends

Analyze waiting times across categories

Compare inpatient vs outpatient trends

Evaluate specialty-level performance

📈 Key Dashboard Pages / Sections

1️⃣ Summary Page

Total patients on waiting list

Year-over-year comparison

KPI cards

Trend analysis

2️⃣ Inpatient Analysis

Monthly admission trends

Time-band distribution

Case type analysis

Specialty breakdown

3️⃣ Outpatient Analysis

Referral trend analysis

Waiting time segmentation

Age profile distribution

Specialty-level filtering

⚙ Technical Implementation

Appended multiple CSV files

Created relationships between fact tables and mapping table

Built DAX measures for KPIs

Implemented slicers for:

Date

Case type

Time band

Specialty

Designed interactive visuals for decision support

💡 Why the Mapping File Was Important

Without the specialty mapping file:

Data would remain code-based and less readable

Users could not analyze performance by department clearly

With the mapping:

Clean, user-friendly specialty names are displayed

Enhanced filtering capability

More business-oriented insights
