COVID-19 Data Exploration
This project involves exploring COVID-19 data to analyze infection rates, death counts, and vaccination progress globally. The analysis leverages SQL techniques including joins, CTEs, temp tables, window functions, and aggregate functions to derive meaningful insights.

Skills Used:
Joins,
Common Table Expressions (CTEs),
Temporary Tables,
Window Functions,
Aggregate Functions,
Creating Views,
Converting Data Types

Key Queries:

Initial Data Exploration: Fetch basic data on COVID-19 cases and deaths, ordered by location and date.

Case vs Death Analysis: Calculate the death percentage relative to total cases for specific locations.
Population vs Cases: Determine the percentage of the population infected by COVID-19.
Infection Rate by Country: Identify countries with the highest infection rates relative to their population.
Death Count Analysis: Find countries with the highest death counts per population.
Continental Analysis: Assess continents with the highest death counts per population.
Global Trends: Analyze global totals and death percentages over time.
Vaccination Data: Compare total population with vaccination rates to assess vaccination coverage.
Rolling Vaccination Data: Use CTEs to calculate rolling vaccination data and its impact on the population.
Data Persistence: Create and populate temporary tables and views for efficient data storage and visualization.
Views and Tables Created:
PercentPopulationVaccinationdata View: Stores cumulative vaccination data for future visualizations.
Temporary Table #PercentPopulationVaccinated: Used for intermediate calculations related to vaccination coverage.
This analysis provides a comprehensive overview of COVID-19 impacts and vaccination progress, utilizing SQL for effective data manipulation and exploration.
