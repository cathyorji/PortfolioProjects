# COVID-19-DATA-EXPLORATION

This project explores data related to the COVID-19 pandemic, specifically looking at data on cases, deaths, and vaccinations across various countries and continents. The project makes use of several SQL techniques such as joins, CTEs, temp tables, window functions, and aggregate functions to analyze and visualize the data.

# Data Sources
The project uses two main datasets:
covid_deaths: This dataset contains information on COVID-19 cases and deaths by location and date.
covid_vaccinations: This dataset contains information on COVID-19 vaccinations by location and date.
Both datasets were obtained from public sources and cleaned for use in this project. The data is downloaded from the Our World in Data and imported into PostgreSQL automatically using the COVID 19 project_csv to PostgreSQL automated code notebook.

# SQL Techniques Used
The following SQL techniques were used in the project:

* Joins: The datasets were joined on location and date to allow for analysis of both cases and vaccinations.
* CTEs: Common Table Expressions were used to perform calculations on partitions of the data, allowing for easier analysis of trends and patterns.
* Temp Tables: Temporary tables were used to store intermediate results of calculations, allowing for further analysis and visualization of the data.
* Window Functions: Window functions were used to perform aggregate calculations on subsets of the data, allowing for more detailed analysis of trends and patterns.
* Aggregate Functions: Aggregate functions were used to summarize the data, such as calculating the total number of cases and deaths across all locations.

# Results
The project produced several interesting insights and visualizations, including:

* The likelihood of dying if you contract COVID-19 in a particular country.
* The percentage of the population infected with COVID-19 in various countries.
* The countries with the highest infection rate compared to their population.
* The countries with the highest death count per population.
* The continents with the highest death count per population.
* The percentage of the population that has received at least one COVID-19 vaccine.

# Conclusion

Overall, this project provides valuable insights into the COVID-19 pandemic and the impact it has had on various countries and continents. The use of SQL techniques such as joins, CTEs, and window functions allowed for more detailed analysis and visualization of the data, highlighting important trends and patterns. This project can be used as a starting point for further analysis of the COVID-19 pandemic and its impact on the world.
