## Project Overview
This project uses Power BI to analyze a healthcare dataset containing patient information, including medical conditions, gender, age, blood type, billing costs, and other metrics. The goal was to identify trends in patient demographics, billing, and hospital stays to support data-driven decision-making in healthcare management.

## Objective
- Clean and structure raw healthcare data to ensure accuracy and consistency
- Explore patterns in patient demographics, billing, and hospital stays
- Visualize insights using interactive Power BI dashboards

## Tools Used
- Microsoft Power BI – data cleaning, visualization, dashboards
- SQL – example queries for aggregation and metric calculation
  
## Analysis Performed
- Imported and cleaned the dataset, standardizing gender values and creating grouped columns for age and length of stay
- Created KPI cards: total patients, total billing, average billing, and average length of stay
- Built bar charts to show:
  - Total billing by medical condition
  - Average billing by medical condition
  - Patient volume by medical condition
  - Average billing by insurance provider
- Added interactive slicers for Gender and Medical Condition to explore trends dynamically
- Optional SQL queries were used to calculate totals, averages, and breakdowns by condition and gender

## Key Insights
- Diabetes is the largest overall cost driver despite not having the highest patient volume
- Obesity has the highest average billing per patient (~$25.8K), cancer the lowest (~$25.2K)
- High patient volume does not always translate to the highest total or average billing
- Gender-based trends reveal nuanced differences. For example: Asthma costs higher for males, arthritis affects more females
  
## Deliverables
- Cleaned and structured Power BI dataset
- Interactive dashboard with KPI cards, charts, and slicers
- Documentation summarizing analysis steps, SQL examples, and insights


