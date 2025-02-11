# Great Britain 🇬🇧

## Overview

- **Key Organizations**: Sheffield Solar - PVLive
- **Data Highlights**: The main estimate of solar outturn in the UK

## Data Sources
# Great Britain Grid Datasets

## 1. Carbon Intensity API

**Source Name:** Carbon Intensity API  
**Link:** [https://api.carbonintensity.org.uk/](https://api.carbonintensity.org.uk/)  
**Historical Data Structure:** Provides both forecast and estimated carbon intensity data, including CO₂ emissions related to electricity generation.  
**Temporal Granularity of Data:** Data is available in 30-minute intervals.  
**Historical Date Range:** Data is available from September 26, 2017, onwards.  
**Updated Outturn Lag:** Data is updated every 30 minutes.  
**Other Data Types:** Offers real-time data, forecasts up to 96 hours ahead, and regional breakdowns.  
**Access:** No API key required; documentation is available at [https://carbon-intensity.github.io/api-definitions/](https://carbon-intensity.github.io/api-definitions/).  

---

## 2. National Grid ESO Data Portal

**Source Name:** National Grid ESO Data Portal  
**Link:** [https://www.neso.energy/data-portal](https://www.neso.energy/data-portal)  
**Historical Data Structure:** Offers various datasets related to system and network operations, demand, and flexibility.  
**Temporal Granularity of Data:** Varies by dataset; includes both real-time and historical data.  
**Historical Date Range:** Varies by dataset.  
**Updated Outturn Lag:** Depends on the specific dataset.  
**Other Data Types:** Includes data on system planning, network development, and operational metrics.  
**Access:** Registration is required for some datasets; API access is available with guidance at [https://www.neso.energy/data-portal/api-guidance](https://www.neso.energy/data-portal/api-guidance).  

---

## 3. UK Power Networks Open Data Portal

**Source Name:** UK Power Networks Open Data Portal  
**Link:** [https://ukpowernetworks.opendatasoft.com/pages/home/](https://ukpowernetworks.opendatasoft.com/pages/home/)  
**Historical Data Structure:** Provides datasets related to electricity networks, including substation locations and transformer flows.  
**Temporal Granularity of Data:** Varies by dataset; some data is available in half-hourly intervals.  
**Historical Date Range:** Varies by dataset.  
**Updated Outturn Lag:** Depends on the specific dataset.  
**Other Data Types:** Includes geospatial data and network asset information.  
**Access:** No registration required; API access is available with documentation at [https://ukpowernetworks.opendatasoft.com/api/explore/v2.1/console](https://ukpowernetworks.opendatasoft.com/api/explore/v2.1/console).  


4. **PV Live**
   - **Link**: [URL here](https://www.solar.sheffield.ac.uk/pvlive/)
   - **Access Notes**: Easy to use API
   - **Historical Data Structure**:
     - Temporal granularity of data: 30 minutely
     - Historical data range: 2013 to present
     - Updated outturn lag?: 24 hours
   - **Other Data Types**: Capacity datasets and forecasts
   - **Access**: Via API and UI

## Additional Comments

* Intraday outturn estimation modelled using ~1000 sites
