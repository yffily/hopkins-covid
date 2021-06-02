# Hopkins-COVID

## Description

Download and visualize the latest COVID-19 data from John Hopkins University. There's nothing original about the visualizations, but there's a useful wrapper function to extract time series for a specific country, state, county, or combination thereof as a pandas dataframe.

## Features

- Automatic download of latest data using gitpython.
- Wrapper function to extract time series for any geographical region. Specify a country/state/county to get a dataframe for that region. Add/subtract those dataframes to get the data for a composite region.
- Visualization of daily cases and deaths time series using matplotlib. The graphic design was inspired by the visualizations from French newspaper *Le Monde*.
- Visualization of cumulative deaths across the world as an interactive map using mplleaflet.

## Author

Yaouen Fily
