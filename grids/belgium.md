# Belgium 🇧🇪

## Overview

- **Key Organizations**: ELIA (Belgian TSO), Open Data ELIA, European Network of Transmission System Operators for Electricity (ENTSO-E)
- **Data Highlights**: 
  - Real-time solar and wind generation data
  - High-quality historical archives
  - Grid data and generation statistics
  - Installed capacity information (11.68 GW solar as of December 2025)

## Data Sources

1. **Open Data ELIA**
   - **Link**: [https://opendata.elia.be/explore/dataset/ods032/table/?sort=datetime](https://opendata.elia.be/explore/dataset/ods032/table/?sort=datetime)
   - **Historical Data Structure**:
     - **Temporal granularity of data**: 15-minute resolution (PT15M)
     - **Historical date range**: 2019-11-02 to present (ongoing)
     - **Updated outturn lag?**: Near real-time (typically within 15 minutes)
   - **Other Data Types**: Solar power generation (measured & upscaled), forecasts, load factors
   - **Access**: No API key required; data available in CSV and other formats

2. **ELIA Grid Data Dashboard**
   - **Link**: [https://www.elia.be/en/grid-data/generation-data/solar-power-generation](https://www.elia.be/en/grid-data/generation-data/solar-power-generation)
   - **Historical Data Structure**:
     - **Temporal granularity of data**: 15-minute resolution (quarter-hour)
     - **Historical date range**: Available (variable by data type)
     - **Updated outturn lag?**: Real-time updates (every quarter hour)
   - **Other Data Types**: 
     - Measured & Upscaled solar generation
     - Day-ahead forecast (D+1, updated at 5:40 p.m.)
     - Day-ahead forecast (D0, intraday, updated hourly)
     - Week-ahead forecast (D+7)
     - Most recent forecast (updated hourly)
     - Power generation factor (relative to monitored capacity)
     - Renewable energy breakdown
   - **Access**: Free access; interactive dashboard with date range selection; data downloadable via ELIA Open Data platform
   - **Monitored Capacity**: 11.68 GW (updated daily)

3. **ENTSO-E Transparency Platform**
   - **Link**: [https://transparency.entsoe.eu/](https://transparency.entsoe.eu/)
   - **Historical Data Structure**:
     - **Temporal granularity of data**: Hourly and daily resolution
     - **Historical date range**: 2015 to present
     - **Updated outturn lag?**: 1–2 days delay
   - **Other Data Types**: Generation, load forecasts, cross-border flows
   - **Access**: Free registration required; API access available with API key

## Additional Comments

- Belgium's solar capacity stands at 11.68 GW (as of December 2025), making it a significant renewable energy contributor.
- ELIA's ODS032 dataset provides comprehensive real-time and historical 15-minute resolution data dating back to November 2019.
- Data includes measured & upscaled values plus multiple forecast horizons (Day Ahead 11AM, Day Ahead 6PM, Week-ahead).
- Data is available in English and Dutch on most platforms.
- Integration with ENTSO-E data provides cross-border electricity flow information.