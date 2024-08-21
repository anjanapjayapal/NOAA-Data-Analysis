## NOAA Temperature Data Analysis
## Overview
This project analyzes NOAA temperature data to identify and visualize record high and low temperatures for the years 2005-2014 and assess if any records were broken in 2015. Additionally, weather stations near Ann Arbor, Michigan, are visualized on a map.

## Data
* Temperature Data: Includes daily temperature records with date and temperature values.
* Weather Stations Data: Includes latitude and longitude of weather stations.

  ## FILES
- `datasets/` 
  - `temperature.csv` - CSV file containing temperature records.
  - `binsize.csv` - CSV file containing weather station locations.
  
- `NOAA-Data-Analysis.ipynb` - Jupyter notebook with code and explanations for temperature data analysis.
- `ann_arbor_stations_map.html` - HTML file with a Folium map visualizing weather stations near Ann Arbor.
  
## Requirements
Python
Pandas
Matplotlib
Seaborn
Folium

## Installation
You can install the required Python packages using pip:
``` bash
pip install pandas matplotlib seaborn folium
```
## Usage
## Temperature Analysis:
* Open the NOAA-Data-Analysis.ipynb notebook in Jupyter.
* Run the cells sequentially to load the data, perform analysis, and visualize results.

## Map Visualization:
* Open the weather_stations_ann_arbor.html file in a web browser to view the map of weather stations.

## Analysis Summary
* Record Highs and Lows (2005-2014): Calculated and plotted daily record high and low temperatures.
* 2015 Record Breaks: Identified and plotted days in 2015 where new high or low temperature records were set.
* Map Visualization: Visualized weather stations within a 50 km radius of Ann Arbor using Folium.
  
## Additional Information
* Leap days were removed from the analysis to ensure consistency across all years.
* Chart enhancements were applied to improve clarity and reduce visual clutter.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the creators of the `folium` library for interactive mapping.
- Data sources and contributors who provided the datasets.

Feel free to adjust the repository URL, license details, and acknowledgments as necessary.
