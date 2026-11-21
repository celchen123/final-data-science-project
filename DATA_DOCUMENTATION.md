All the data comes from Open-Meteo (open-meteo.com), a free weather API.
Weather (temperature, precipitation, humidity) is from its historical archive, which is based on a reanalysis, a model fitted to past observations.
Air quality and pollen are from its Air Quality API, which uses the CAMS atmospheric model (Copernicus Atmosphere Monitoring Service).

There are 980 rows (four cities of Berlin, Budapest, Lyon, Seville times 245 days March 1 to October 31, 2025) and 21 columns. The columns are: date, (YYYY-MM-DD), in the city’s local time, city name, latitude, longitude, average temperature of the day (°C), Hottest hour of the day (°C), Coldest hour of the day (°C), total precipitation (mm), Average relative humidity (%), daily PM2.5 mean (µg/m³), daily PM10 mean (µg/m³), daily nitrogen dioxide mean (µg/m³), daily ozone mean (µg/m³), daily sulfur dioxide mean (µg/m³), daily carbon monoxide mean (µg/m³), highest hourly count of alder pollen, birch, grass, mugwort, olive, ragweed (grains per cubic meter).

Something to keep in mind is that certain cities have certain pollen species that are most prevalent. There may not be a high pollen count for the less prevalent pollen types.
Berlin: alder, birch, grass and mugwort
Budapest: ragweed, grass, birch
Lyon: ragweed, grass and birch.
Seville: olive and grass
