# python-api-challenge

Solution to Python API challenge, performing basic data analysis using the OpenWeatherMap and Geoapify APIs to complete the analysis of cities located based on randomized latitude and longitude pairs.

The code then looks up weather conditions in each location, plots them on a map.  Finally, the code filters the locations based on desirable locations, specifically, ones:
- With Max Temperatures < 85 degrees Fahrenheit
- North of 50 degrees North or South of -35 Latitude
- Longitude < 20  or > 140 degrees
- Is one of selected countries: NO, IS, DK, SE, SJ, FO, GL, or NZ 
