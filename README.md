# International_Population
This project presents a cleaned and visualized dataset of international population data using Power BI.

## Project Structure

- `data/` – Raw and cleaned data files
- `.gitignore` – Files to exclude from version control
- `LICENSE` – Open-source license (MIT)
- `README.md` – Project overview and instructions
- `International_Population.pbix`: Power BI dashboard file
  
## Dashboard Overview

The Power BI dashboard provides:
- Total and regional population breakdowns
- Comparative trends across countries
- Measures created to allow filtering by years
- When no year is selected, visualizations default to 2025

## Data
This dataset was downloaded from [United States Census Bureau](https://www.census.gov/data-tools/demo/idb/#/table?dashboard_page=country&COUNTRY_YR_ANIM=2025&menu=tableViz).

## Data Cleaning Steps (Power Query)

1. **Renamed Columns**  
   All column headers were standardized for readability and consistency.

2. **Changed Data Types**  
   Columns were converted to appropriate data types.

3. **Checked for Duplicates**  
   Duplicate rows were checked and confirmed to be absent.

## Tools Used

- **Power BI** for visualization and transformation
- **Power Query** for in-dashboard data cleaning

##  Next Steps

This dashboard provides a foundation for demographic trend analysis. Future additions may include:
- Dependency ratio visualizations
- Age group comparisons
- Regional heatmaps

