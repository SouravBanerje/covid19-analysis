# COVID-19 Interactive Analysis Shiny App

This Shiny app provides an interactive analysis of COVID-19 data, including maps, trends, summaries, and comparisons. It allows users to select countries and dates to visualize and analyze the impact of the pandemic over time.

## Features

- Interactive map displaying total COVID-19 cases by country.
- Trend plots for new cases, new deaths, total cases, total deaths, cases per million, and deaths per million.
- Summary table of selected data.
- Detailed statistics and vaccination data.
- Comparison plots for new cases and new deaths between selected countries.

## Data Sources

- COVID-19 data from [Our World in Data](https://github.com/owid/covid-19-data)
- Country coordinates data

## Requirements

- R (version 4.0.0 or later)
- R packages: `shiny`, `tidyverse`, `plotly`, `DT`, `shinythemes`, `leaflet`, `leaflet.extras`

## Installation

1. Install R from [CRAN](https://cran.r-project.org/).
2. Install the required R packages:

```R
install.packages(c("shiny", "tidyverse", "plotly", "DT", "shinythemes", "leaflet", "leaflet.extras"))
