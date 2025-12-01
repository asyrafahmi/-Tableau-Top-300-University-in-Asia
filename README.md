📊 TOP 300 Asian Universities – Tableau Visualization Project
CSEB5133 – Data Visualization Programming (Final Project)


🌟 Project Overview

This project analyzes the Top 300 Universities in Asia using data visualization techniques in Tableau.
It consists of data preparation, data integration, multi-chart visualizations, interactive dashboards, geospatial analysis, and calculated metrics.

The final deliverable includes two interactive dashboards and one story, published on Tableau Public.

🔗 Live Dashboard (Tableau Public)

👉 https://public.tableau.com/app/profile/muhamad.asyraf.fahmi.mohd.saiful.hazmi/viz/SW01082352TOP300UNIASIA/UniversityPerformanceandReputation

📁 Project Components
1. Data Sources & Integration

Multiple CSV datasets joined:

rank.csv (primary)

location.csv

academicExcellence.csv

globalImpact.csv

reputation.csv

Inner joins and unions used to merge datasets.

2. Data Preparation (Tableau Prep)

Removal of null values

Converting data types (text → numeric)

Cleaning columns and renaming fields

Exported cleaned data for use in Tableau Desktop

3. Visualizations

Includes:

Bar charts

Line charts

Combined axis & dual-axis charts

Trend-line analysis

Scatter plots

Tables with highlight actions

Key analyses:

University overall ranking

Country ranking

Citations per paper vs papers per faculty

Academic reputation trends

Employer reputation trends

International student & faculty distribution

Exchange program participation

4. Calculated Fields

Example:

Research Impact Score = [Citations per Paper] + [Papers per Faculty]

5. Mapping

Used latitude/longitude from dataset

Plotted university performance by country

Custom map layers for better visibility

6. Dashboards
Dashboard 1: University Performance & Reputation

Overall ranking

Research impact metrics

Academic & employer reputation

Interactive filters for universities/countries

Dashboard 2: International Collaboration & Student Dynamics

Geographic distribution

International student & faculty rates

Exchange program comparisons

Country performance metrics

7. Storytelling

Story with 2 tabs:

Tab 1 → Dashboard 1

Tab 2 → Dashboard 2

Includes key insights and narrative explanation

🧩 How to Use

Open the Tableau Public link

Use the filters to explore universities, countries, or performance categories

Switch between dashboards using the story navigation

📦 Repository Contents
/data               → raw datasets (CSV)
/prep_output        → cleaned datasets
/screenshots        → images of dashboards
README.md           → project documentation

🛠️ Tools Used

Tableau Desktop

Tableau Prep Builder

Tableau Public

Microsoft Excel

📚 Key Insights

China dominates Asian university rankings (overall score 100).

Older universities show significantly higher academic & employer reputation.

Hong Kong, Singapore, and Macau lead in international student/faculty diversity.

Research output strongly correlates with citation impact.
