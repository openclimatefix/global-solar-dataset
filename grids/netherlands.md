# Netherlands 🇳🇱

## Overview

- **Key Organizations**: NED NL and TenneT (via ENTSO-E)
- **Data Highlights**: 2 different solar outturn benchmarks and forecasts available.

## Data Sources

1. **TenneT via ENTOSO-E**

   - **Link**: [URL here](https://transparency.entsoe.eu/generation/r2/actualGenerationPerProductionType/show?name=&defaultValue=false&viewType=TABLE&areaType=BZN&atch=false&datepicker-day-offset-select-dv-date-from_input=D&dateTime.dateTime=10.01.2024+00:00|CET|DAYTIMERANGE&dateTime.endDateTime=10.01.2024+00:00|CET|DAYTIMERANGE&area.values=CTY|10YNL----------L!BZN|10YNL----------L&productionType.values=B16&dateTime.timezone=CET_CEST&dateTime.timezone_input=CET+(UTC+1)+/+CEST+(UTC+2)#)
   - **Historical Data Structure**:
     - Temporal granularity of data: 15 minutely
     - Historical date range: 2019 to present
     - Updated outturn lag?: No lag visible from UI, live outturn.
   - **Other Data Types**: Day ahead and Intraday solar forecasts, generation and capacity datasets.
   - **Access Notes**: registration required, can download data via the UI.
2. **Nationaal Energie Dashboard (NED)**

   - **Link**: [Solar Data](https://ned.nl/nl/dataportaal/energie-productie/elektriciteit/zonne-energie)
   - **Data Type**: Historical hourly solar outturn back to 2017, 7 day hourly forecast.
   - **Historical Data Structure**:
     - Temporal granularity of data: Hourly via UI and 15 minutely via API
     - Historical data range: 2017 to present
     - Updated outturn lag?: 1 hour
   - **Other Data Types**: 7 day solar forecast, capacity, real-time
   - **Access**: Easy to access, create an account and can use the UI to download data. API also available

## Additional Comments

- NED model the generation of solar energy from everyone (households to solar farms), essentially modelling behind the meter solar. The consumption of the generated solar electricity is not inlcuded in the outturn.
