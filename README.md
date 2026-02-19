# Codealpha-Netflix-EDA
This project was completed during my Data Analytics Internship at Codealpha!

Netflix Data Trends Analysis
Internship Project Overview:
This project was developed during my Data Analytics Internship at [Codealpha] (https://www.codealpha.tech/). I was tasked with analyzing the Netflix library to identify content gaps, regional trends, and thematic clusters.

Dashboard View:
Full interactive view of the Netflix Analysis Dashboard developed in Power BI.
![Image alt](https://github.com/srushtibharti15/Codealpha-Netflix-EDA/blob/8f6d05f2c0d075139c31cb8c6382853f971791e2/Screenshot%202026-02-19%20181845.png)

 Project Goals & Insights:
Based on the project requirements from [Company Name], I focused on three key analytical pillars:

1. Global Content Distribution
Findings: My analysis confirmed that Movies represent the majority of the catalog. The United States and India emerged as the primary content hubs.

2. Content Evolution (The 2015 Surge)
Findings: I identified a massive spike in content additions starting in 2015. This data visualization highlights Netflix's aggressive shift toward original programming in the last decade.

3. Thematic Keyword Detection (Advanced DAX)
Findings: To go beyond standard genres, I built custom logic to scan descriptions for "Suspense" and "Crime" themes.

Technical Detail: I used a custom calculated column to flag titles containing keywords like Murder, Mystery, or Thriller.

Technical Workflow:
Data Cleaning: Handled missing values in netflix_titles.csv, removed duplicates, and corrected date formats.
Transformation: Filtered out inconsistent category types to ensure data accuracy.
Visualization: Built an interactive multi-page report in Power BI with cross-filtering capabilities.

Repository Contents
EDA.pbix: The source Power BI file.
netflix_titles.csv: The raw dataset.
EDA Report.docx: Detailed documentation and methodology.
/screenshots: High-resolution captures of the analysis.
