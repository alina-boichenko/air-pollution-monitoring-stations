## Air Pollution Monitoring Stations

This project analyzes data on PM10 air quality monitoring stations across six countries. I calculate the density of PM10 stations per 1,000 square kilometers for each country using geographic data and station counts.

### Task

Using the provided geojson data for air pollution monitoring stations and country boundaries, calculate the density of PM10 monitoring stations per 1,000 square kilometers for each of the following countries: US, UK, Turkey, Thailand, Philippines, and India. Rank the countries by density in descending order and present your results in a simple table, showing:

Country Name
Number of PM10 Stations
Area (in square kilometers)
Density of PM10 Stations per 1,000 sq. km

Data Sources
Stations: https://api.energyandcleanair.org/stations?country=GB,US,TR,PH,IN,TH&format=geojson
Country Boundaries: https://datahub.io/core/geo-countries

### Required Libraries

The following libraries are required to run the project:
```
pandas — for data manipulation.
pyproj — for calculating country area and perimeter.
shapely — for working with geometric data.
requests — for fetching PM10 station data.
```
To install dependencies, run:

```
pip install pandas pyproj shapely requests
```

Clone the repository:
```
git clone https://github.com/alina-boichenko/air-pollution-monitoring-stations.git
```

Start Jupyter Notebook:
```
jupyter notebook
```

Open the corresponding .ipynb file and follow the instructions.
