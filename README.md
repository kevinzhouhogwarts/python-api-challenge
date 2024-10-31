# python-api-challenge

## Introduction
Using an API call, weather data for several cities was retrieved. Regression was performed and visually on scatter plots of several weather variables versus latitude.

## Method
The supplied code for generating latitudes and longitudes and for identifying the cities closest to those coordinate pairs was used.

For the OpenWeatherMap API, the 5 day weather forecast API was chosen, since it provided both a maximum temperature and the country code. Instead of requesting all 40 possible forecasts within the 5 day period used for each API request, the query parameter cnt was changed to request just 1 for brevity.

For weather trends tend to mirror across the equator, city weather data was split between Northern and Southern hemisphere subsets, then plotted and regressed separately.

## Conclusions
