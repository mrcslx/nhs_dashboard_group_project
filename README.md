
# Group Project - Public Health Scotland Dashboard

## Overview

This repository contains an RShiny dashboard application and additional files for testing and exploring the data used. The dashboard allows users to explore data through four tabs which include an array of interactive visualisations. The aim of the project was to assist Public Health Scotland in determining whether or not there has been a winter crisis in NHS Scotland within the acute care sector over the last four years.

[Launch Dashboard](https://mrcslx.shinyapps.io/dashboard_app/)

[View Presentation Slides](https://mrcslx.github.io/phs_dashboard_slides.pdf)

## Team Members

Our team was made up of four members:

- Tom Keeling
- Oscar Chapman
- Michael Kustra
- Marcus Eilertsen

## Process Methodology

All datasets used were sourced from Public Health Scotland's Scottish Health and Social Care Open Data. The data was cleaned and wrangled, and four KPIs were drawn out:

- Hospital Admittance Rates
- Hospital Bed Occupancy
- Hospital Wait Times
- Mortality

These were then filtered to show various discoveries as visualisations within each relevant tab.

## Packages Used

`tidyverse`, `sf` and `lubridate` were the primary tools used to clean, explore and wrangle the data.

`ggplot2`, `ggplotly` and `leaflet` were all used to create visualisations.

`shiny` and `shinydashboard` were used to build the structure of the dashboard.

## App Functionality

The app has four tabs which display data on different topics:

- Overview - allow the user to gain a global understanding of the KPIs and data used
- Effects of Covid - allows the user to explore the effects of Covid across three different KPIs
- Geographic Analysis - contains two interactive maps comparing health-board and hospital specific data
- Demographic Analysis - allows the user to view the data by age group, deprivation and gender

## Screenshots

### Overview Tab
![](screenshots/overview.png)

### Effects of Covid Tab
![](screenshots/pre_post.png)

### Geographic Analysis Tab
![](screenshots/geog.png)

### Demographic Analysis Tab
![](screenshots/demo.png)

## References

All data was sourced from the Scottish Health and Social Care Open Data platform, which is managed by Public Health Scotland.

- https://www.opendata.nhs.scot/
