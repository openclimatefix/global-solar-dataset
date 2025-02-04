# Germany 🇩🇪

## Overview
- **Key Organizations**: Federal Network Agency (Bundesnetzagentur), ENTSO-E Transparency Platform, Fraunhofer ISE, Open Power System Data (OPSD)
- **Data Highlights**: 
  - Real-time generation data for renewables and conventional sources
  - High-quality historical archives spanning decades
  - Monthly and annual updates on energy statistics and capacity
  - Detailed breakdowns of solar, wind, hydro, and biomass contributions

## Data Sources

### 1. **ENTSO-E Transparency Platform**
- **Link**: [https://transparency.entsoe.eu/](https://transparency.entsoe.eu/)
- **Access Notes**: Free registration required. API access available with an API key.
- **Historical Data Structure**:
  - **Temporal granularity of data**: Hourly and daily resolution
  - **Historical data range**: 2015 to present
  - **Updated outturn lag?**: Typically updated with a delay of 1–2 days
- **Other Data Types**: Includes real-time generation, load forecasts, and cross-border flows
- **Access**: [ENTSO-E API Docs](https://transparency.entsoe.eu/content/static_content/Static%20content/web%20api/Guide.html)

### 2. **Open Power System Data (OPSD)**
- **Link**: [https://open-power-system-data.org/](https://open-power-system-data.org/)
- **Access Notes**: Fully open data. No registration or API key required.
- **Historical Data Structure**:
  - **Temporal granularity of data**: Hourly and daily resolution
  - **Historical data range**: 2006 to present (varies by dataset)
  - **Updated outturn lag?**: Updated monthly
- **Other Data Types**: Includes time series for generation, load, weather, and installed capacities
- **Access**: [OPSD Tutorials](https://github.com/Open-Power-System-Data/datapackage_tutorial)

### 3. **Fraunhofer ISE Energy Charts**
- **Link**: [https://www.energy-charts.info/](https://www.energy-charts.info/)
- **Access Notes**: Free and open access. No registration required.
- **Historical Data Structure**:
  - **Temporal granularity of data**: Hourly, daily, monthly, and yearly resolution
  - **Historical data range**: 2000 to present
  - **Updated outturn lag?**: Updated weekly or monthly
- **Other Data Types**: Focuses on renewable energy generation, fossil fuel usage, and CO2 emissions
- **Access**: Downloadable Excel files available

## Additional Comments
- **API Access**: If you plan to use APIs (e.g., ENTSO-E), ensure you understand rate limits and authentication requirements.
- **Language**: Most German datasets are available in English, but some metadata may be in German. Use translation tools if needed.
- **Data Quality**: Germany's energy data is considered highly reliable due to strict regulatory oversight and transparency initiatives.
