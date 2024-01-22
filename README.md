# London Bike Sharing Dataset

# Content
The data is acquired from 3 sources:

1. Https://cycling.data.tfl.gov.uk/ 'Contains OS data © Crown copyright and database rights 2016' and Geomni UK Map data © and database rights [2019] 'Powered by TfL Open Data'
2. freemeteo.com - weather data
3. https://www.gov.uk/bank-holidays From 1/1/2015 to 31/12/2016 The data from cycling dataset is grouped by "Start time", this represent the count of new bike shares grouped by hour. The long duration shares are not taken in the count.

# Metadata:
1. "timestamp" - timestamp field for grouping the data
2. "cnt" - the count of a new bike shares
3. "t1" - real temperature in C
4. "t2" - temperature in C "feels like"
5. "hum" - humidity in percentage
6. "wind_speed" - wind speed in km/h
7. "weather_code" - category of the weather
8. "is_holiday" - boolean field - 1 holiday / 0 non holiday
9. "is_weekend" - boolean field - 1 if the day is weekend
10. "season" - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.

# "weather_code" category description:

- 1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity
- 2 = scattered clouds / few clouds
- 3 = Broken clouds
- 4 = Cloudy
- 7 = Rain/ light Rain shower/ Light rain
- 10 = rain with thunderstorm
- 26 = snowfall
- 94 = Freezing Fog
