# Codealpha-Netflix-EDA
This project was completed during my Data Analytics Internship at Codealpha!

Netflix Data Trends Analysis
Professional Overview:
This Exploratory Data Analysis (EDA) project was developed as part of my internship at Company Name. The goal was to provide data-driven insights into Netflix’s content strategy to assist in decision-making processes regarding library expansion and regional focus.

Project Goals:
The primary objective of this internship task was to extract meaningful insights from raw data, specifically focusing on:
Growth Trends: Visualizing the massive content surge post-2015.
Content Split: Comparing the volume of Movies vs. TV Shows across different regions.
Thematic Search: Building a custom system to identify "Thriller" and "Murder Mystery" themes.

Technical Implementation:
Data Cleaning & Preparation
Before visualization, I performed the following preprocessing steps to ensure data integrity:
Duplicate Removal: Identified and removed redundant entries from the netflix_titles.csv.
Data Type Correction: Standardized date_added and release_year formats for time-series analysis.
Filtering: Removed incorrect category values from the type column to ensure a clean split between Movies and TV Shows.

Advanced Analysis (DAX & Custom Logic)
To go beyond basic charts, I created a custom keyword-based detection system. Using a calculated column, I used logic to scan the description field for specific keywords:

Logic: If the description contained "Murder," "Mystery," "Thriller," or "Crime," it was tagged as a Suspense/Crime Theme.

Purpose: This allowed the company to see the prevalence of these high-performing genres even when they weren't explicitly listed in the primary category.


Project Structure
EDA.pbix: The full interactive Power BI dashboard.

netflix_titles.csv: The source dataset.

EDA Report.docx: A detailed technical report outlining the methodology and findings.
