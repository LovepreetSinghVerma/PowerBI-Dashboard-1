# *PowerBI-Dashboard*

This repository contains a Power BI dashboard visualizing import/export data by country and year. The data is sourced from the DatasetPowerBI.csv file.

Dashboard Overview
The dashboard includes the following visualizations:
Bar chart showing import/export value over time for selected country
Pie chart showing import/export value by country for selected year
Table showing detailed import/export data
The visualizations allow users to filter by country and year to analyze trends in the data. Slicers are included to easily change the filters.

Data
The DatasetPowerBI.csv file contains import/export data for several countries from 1995-2016. The data includes:

Country
Year
Unit of measurement (USD, units, kW)
Import/Export value
There are some issues with inconsistent units in the source data that required cleanup. Some years are missing for certain countries.

Installation
To use this dashboard yourself:
Download the Dasboard(Internal Combustion Engines In 10 Countries).pbix file
Import into Power BI
Load the data into the Power BI model
Build visualizations and dashboard
You may need to do some data transformations when loading the data to handle the inconsistent units and missing values.

Usage
The dashboard filters allow you to:
Select specific countries to analyze
Change the year filter to see trends over time
Highlight specific points in time with the play axis animation

Issues
Some potential issues and limitations with the current dashboard:
Inconsistent units in the source data make analysis difficult
Missing years for some countries
Hardcoded years and countries, not easy to extend dashboard for new data
Limited interactivity between visuals (filter propagation)
Future iterations could focus on cleaning the data for consistency, adding parameters for dynamic filtering, and linking visuals together.
