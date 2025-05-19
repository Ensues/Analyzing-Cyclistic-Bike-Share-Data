
# How Does a Bike-Share Navigate Speedy Success? 
  <p align="center">
    <img alt="Excel" src="https://img.shields.io/badge/excel-008000?style=for-the-badge&logo=google-sheets&logoColor=white" />
    <img alt="Sheets" src="https://img.shields.io/badge/Sheets-008000?style=for-the-badge&logo=google-sheets&logoColor=white" />
    <img alt="Tableau" src="https://img.shields.io/badge/Tableau-ffffff?style=for-the-badge&logo=Tableau&logoColor=black" />
    <img alt="SQL" src="https://img.shields.io/badge/-SQL-000?style=for-the-badge&logo=MySQL&logoColor=4479A1" />
    <img alt="Google Query" src="https://img.shields.io/badge/Google_Query-3670A0?style=for-the-badge&logo=Google_Query&logoColor=white"/>
  </p>

## Table of Contents
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Methodology Summary](#methodology-summary)
- [Key Findings & Insights](#key-findings--insights)
- [Future Work](#future-work)


---

## Project Overview
Examined a Cyclistic’s bike-share database to uncover behavioral differences between annual members (Subscribers) and casual riders (Customers).

Using a full 12-month dataset, I cross analyzed and validated seasonal trends and usage patterns through three tools: Google Sheets, Tableau Public, and Google BigQuery (SQL).


Derived insightful information that forms the basis for targeted digital marketing strategies aimed at converting casual riders into loyal annual members.



---

## Tools & Technologies
- **Google Sheets** - For data cleaning, manipulation, and initial pivot table analysis.
- **Tableau Public** - To create interactive dashboards and visualizations.
- **Google BigQuery (SQL)** - Re-analyzed the cleaned data for cross vaidation of results.

*Note: R integration was planned for future analysis but is not included in the current project scope.*


---

## Repository Structure
- **Data** - Raw and cleaned datasets.
- **SQL** - BigQuery queries and output results.
- **Visualizations** - [Tableau Public dashboard link](https://public.tableau.com/app/profile/eric.janssen.quiambao/viz/CyclisticBike-ShareAnalysisRidePatternsandUserInsightsV2/CyclisticBike-ShareAnalysisRidePatternsandUserInsights) and screenshots.
- **Documentation** - Detailed project documentation and analysis summaries.


---

## Methodology Summary

The project follows a structured six-phase data analytics process: Ask, Prepare, Process, Analyze, Share, and Act.
- **Ask** - Define business questions and objectives.
- **Prepare** - Gather and clean a 12-month dataset with key fields (e.g., start_time, ride_length, user_type, etc.).
- **Process** - Transform data in Google Sheets, create pivot tables and charts, and remove unnecessary columns.
- **Analyze** - Use pivot tables in Sheets, interactive dashboards in Tableau Public, and SQL queries in BigQuery to uncover behavioral differences between Subscribers and Customers.
- **Share** - Publish findings via an interactive Tableau dashboard and detailed GitHub documentation.
- **Act** - Develop targeted marketing recommendations based on the analysis.

---

## Key Findings & Insights

- **Ride Duration** - Customers average longer ride durations (approximately 27–33 minutes) compared to Subscribers (around 11–13 minutes).
- **Usage Patterns** - Subscribers have higher ride counts on weekdays, indicating commuter usage, while Customers show peak activity on weekends.
- **Time-of-Day Trends** - Subscribers tend to ride during early and late working hours, consistent with typical commutes, whereas Customers ride more consistently throughout the day with a notable surge on weekends.

These insights form a robust foundation for developing targeted digital marketing strategies aimed at converting casual riders into loyal annual members.

---

## Future Work

Future enhancements include integrating advanced statistical analysis using R to refine insights further and exploring additional interactive features and segmentation (e.g., by age group or specific stations) for more granular recommendations.
