# Trave Destination Project
The aim of this project is to create a tool to assist its users to determine their next travel destination. At its current stage the project offers the possibility for the users to determine their travel destination based on the desired weather conditions worldwide.

## Project steps
1. Data collection: From online sources, weather data from Meteostat library
2. Data pipeline: Python scripts to clean and structure the data
3. Postgres data warehouse/database: Python scripts to connect to a database and create SQL tables
4. Visualisation: A dashboard in Tableau visualising a temperature map with relevant filters and supporting graphs to investigate deeper

## Future iterations
- Adding more indicators to help determine travel destination: safety index, cost of living, etc.
- Adding more weather data to data warehouse: Adding ability filter weather by city.
- Web app: Functionality to implement ad-hoc requests by cities wordlwide, eliminating need to store large amounts of data.
- AI support in web app: Utilising AI to give users more details on travel destinations and things to do.

## Data warehouse
![dwh_design](https://github.com/vltnnx/Travel-Destination-Project/blob/main/warehouse_design/travel_destination_db.png?raw=true)
<br><br>

## Visualisations
Visualisation for the project created in Tableau. Find the interactive dashboards on Tableau Public via links below.

#### Temperature dasboard
Dashboard visualising monhtly temperature and precipitation data all around the world. Try yourself [through this link](https://public.tableau.com/views/WorldWeather_17150782341070/Dashboard?:language=en-GB&publish=yes&:sid=&:display_count=n&:origin=viz_share_link).
![Tableau Dashboard](https://github.com/vltnnx/Travel-Destination-Project/blob/main/img/fig1_weather%20map.png?raw=true)

#### Quality of life dashboard
Highlighting countries and adjusting colour scale on the map based on user filters. Dashboard allows one to filter destination countries based on average monthly temperature, safety, affordability, pollution, and health care quality data. Try the dashboard [through this link](https://public.tableau.com/views/TravelDestinationPriority/TravelDestinationPriority?:language=en-GB&publish=yes&:sid=&:display_count=n&:origin=viz_share_link).
![Tableau Dashboard](https://github.com/vltnnx/Travel-Destination-Project/blob/main/img/fig1_weather%20map.png?raw=true)