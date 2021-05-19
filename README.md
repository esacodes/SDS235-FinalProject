# SDS235-FinalProject

Carol Milton, Nage Ngo, and Esa Schenck


## Data

Our dataset was downloaded from the U.S. Government’s Open Data source, Data.gov. The specific dataset, **Mental_Health_Care_in_the_Last_4_Weeks.csv**, is metadata published by the Centers for Disease Control and Prevention (CDC) from the Household Pulse Survey. It contains aggregate statistics for four mental health indicators in U.S. adults between mid-August 2020 and late March 2021.

**Mental_Health_copy.csv**: the copy of the original mental health data set with duplicate rows 2738, 2831 removed.

**Census-EST2019.csv / xlsx**: Population data from the US government Census Department.

**us.csv**: US-level data - The daily number of newly reported cases and deaths nationwide, including all states, U.S. territories and the District of Columbia.

**states.csv**: State-level data

**covid_dated_fixed.csv**: NYT COVID data combined with the periods of the mental health data.

**data_correct_dates.csv**: Mental health data with date variable corrected in preparation for joining with the COVID data.

**new_data_fixed.csv**: The cleaned dataset; **covid_dated_fixed.csv** and **data_correct_dates.csv** joined; also the dataset used in
**final_scatterplots.Rmd** to generate visualization for the relationship between the COVID severity and mental health access.

## Exploration and Visualization

**esas_exploratory.Rmd**: Data wrangling and exploration.

**final_scatterplots.Rmd**: Polished scatterplots showing trends in the values for each mental health indicator relative to the severity of the pandemic.

**nh_explore.Rmd**: Data wrangling and interactive graph code for the Interactive Choropleth Maps.

The html files are the knitted output of the markdowns.

## Packages Used for Wrangling and Visualization

tidyverse, RColorBrewer, gridExtra, ggplot2, lubridate, usmap, map, multiscales (clauswilke/multiscales: Multivariate scales for 'ggplot2')
